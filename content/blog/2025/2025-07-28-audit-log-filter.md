---
title: "Audit Log Filter Component"
date: "2025-07-28T00:00:00+00:00"
tags: ['Opensource', 'Audit Log', 'filter', 'component', 'MySQL', 'Community']
categories: ['MySQL', 'Community']
description: "Lets review the audit log filter component in MySQL 8.4.
authors:
  - wayne
images:
  - blog/2024/06/dna-microscopic-view.jpg
---
The audit log filter component in MySQL 8.4 is a powerful tool for auditing database activity. However, it can be difficult to understand how it works and how to use it effectively. In this article, we will review the audit log filter component in MySQL 8.4 and provide some tips for using it effectively.

### Enabling Audit Log Filter
We will be using Percona Server 8.4.4 or higher in the examples below. First, we need to enable the audit log filter component. To install the audit log filter component, we need to run the following command:
```
mysql -u root -p < /usr/share/percona-server/mysql/share/audit_log_filter_linux_install.sql
```
Verify that the audit log filter component is enabled by running:
```
select * from mysql.component;
+--------------+--------------------+-----------------------------------+
| component_id | component_group_id | component_urn                     |
+--------------+--------------------+-----------------------------------+
|            2 |                  1 | file://component_audit_log_filter |
+--------------+--------------------+-----------------------------------+
1 row in set (0.00 sec)
```

This will install the component and create 2 new tables in the database: `audit_log_filter` and `audit_log_user`. These two tables are used to store the audit log filter configuration and the user information for the audit log filter. We will call there the audit log filter tables.

```
+------------------------------------------------------+
| Tables_in_mysql                                      |
+------------------------------------------------------+
| audit_log_filter                                     |
| audit_log_user                                       |
```
Update the my.cnf with type of output we want and the location of the audit.log file:
```
[mysqld]
# auditlog 
audit_log_filter.format=JSON
audit_log_filter.file=/var/lib/mysql/audit.log
```
Restart mysql server to apply the changes:
```
sudo systemctl restart mysqld
```
The audit log filter install is complete. Now we can start using the audit log filter component. 

### Creating Audit Log Filters
The audit log filter component in MySQL 8.4 allows us to create an audit log filter. An audit log filter is a set of rules that define which events should be logged and which events should be ignored. The audit log filter component is a powerful tool for auditing database activity.

Lets create a rule that will log all events:
```
SELECT audit_log_filter_set_filter('log_all_events', '{ "filter": {"log": true } }');
```
Lets assign the rule to the user:
```
SELECT audit_log_filter_set_user('%', 'log_all_events');
SELECT audit_log_filter_flush();
```
Now all users will have all their events logged. Lets create a rule that will log all events except for the ones that start with the word "update":
```
SELECT audit_log_filter_set_filter('log_all_except_update', '{ "filter": {"log": true, "except": {"update": true } } }');
SELECT audit_log_filter_flush();
```
