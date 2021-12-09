---
title: "Get Involved in Databases on Kubernetes (DoK) Community - Percona Podcast 14"
description: "Matt and Bart sit down to talk about what is happening in the community, how people can get involved, and what fun things are coming up next."
short_text: "Bart Farrell heads up the Data on Kubernetes community (DoK). Matt and Bart sit down to talk about what is happening in the community, how people can get involved, and what fun things are coming up next. "
date: "2021-03-17"
podbean_link: "https://percona.podbean.com/e/the-hoss-talks-foss-ep14-databases-on-kubernetes-bart-farrell-the-head-of-the-dok-community/"
youtube_id: "thE_-d4PvcA"
speakers:
  - bart_farrell
aliases:
    - "/podcasts/14/"
url: "/podcasts/14-get-involeved-in-databases-on-kubernetes-dok-community"
---

 ## Transcript
 
**Matt Yonkovit:**
Everybody, I'm here with Bart Farrell, a quote-unquote, community builder for the Data and Kubernetes community. Bart, thanks for joining us today. I really appreciate having you. Now, a lot of people don't know what Docker data on Kubernetes is. Maybe you could just start with that and explain what is this organization?

**Bart Farrell:**
Okay, well, first of all, thanks a lot for me, HOSS. Great to be here. And so the Data on Kubernetes community is an open space and independent space, where folks are free to come in and share stories, share use cases, share war stories, and learn from and learn from other people that are that have stories to share and experiences regarding how to run stateful workloads on Kubernetes. And so there are lots of different angles behind that whether we're talking about databases, or operators or networking, all the different things, storage, of course, all the different things that can come into that space. So we have meetups every week. Fantastic people from all over the world talking about their experiences, and helping people have like we can say like a to-do list or like a method when they want to approach this, this topic of running stateful workloads on Kubernetes.

**Matt Yonkovit:**  
And stateful workloads are hard and Kubernetes really wasn't originally designed for that. Right?

**Bart Farrell:** 
This is it. And this sort of can we shoehorn this in there for something that originally didn't have this in mind? What I've seen, though, is from talking to more and more people is that people like you know, it, I've you know, I've been thinking about this for a while and wondering what are we going to get to that point, we can talk about things being ephemeral, but and then other people that even come in and say there’s no such thing as stateless. Everything at some point is in some kind of a state that gets controversial. But like I said, the more and more that I'm talking to people, the more and more it does seem that there are use cases that it's not just a what-if kind of thing, it's you know like I did it this way. So I think we're kind of trying to do is standardize and maybe codify some of these processes, so that it is easier when the use cases, right. So that people know how to do things.

**Matt Yonkovit:**  
Yeah, and I think there's a huge demand right now everybody wants to run as much as they can on Kubernetes. Because everybody wants their own application stack. Every developer wants their own database, they want their own playground to play with. And you’re talking 1000s or 10s of 1000s or hundreds of 1000s of potential instances of applications that are out there running our microservices. It's just a lot of stuff and wrangling that rodeo is really hard. Yeah, and I think that's really appealing to a lot of folks. Now. Now, how did you get involved in this community? Like, like, where did you start? I mean, like, very, it's, it's kind of an interesting space. So what got you super interested?

**Bart Farrell:** 
This is it? That's a great question. And it's a great opportunity for me in terms of like100%, transparency, full disclosure, we’re in open source space, and I think it's really important to be as open as possible. So my background, in terms of academically and I'm curious, I'm curious, your background as well, too, is that I got my undergraduate degree in religious studies. But that will play a role later on. Because at the end of the day, we're talking about beliefs. We're talking about evangelism, we're talking about groups that have leaders and certain sort of ways of thinking. And I got into tech, though, around five years ago, I'm living in living in Spain, originally from Northern California. And I got into tech, working in telemanagement, event organization communication. And it turned out that, the company that I was working in was a British company focused on E-commerce software. So they were they got into Kubernetes, towards the end of 2017, beginning of 2018, prior to that with Docker and mezzos. And so I by chance, my desk was next to the DevOps team, so I was hearing them about all the cultural changes that were going on, first of all, getting into the cloud, and then additionally, adding this other element of Kubernetes. So it's in that for I was in that company for about three years. Then I started working on my own as a freelancer for the last two and a half years. And a friend of mine had started the community last year in July, my buddy Demetrius, who also is involved in other tech communities around ml ops, shout out to Demetrius, and he, for a couple of different reasons, wasn't going to be able to continue with it. It was like, Hey, would you be interested in doing this? I was like, Whoa, this is kind of a tall order. But luckily, from a lot of really supportive people in the community and, and Demetrius himself that transitioned in. And so since then, I've been meeting lots and lots of interesting people, communities growing, we're doing stuff in other languages. We have meetups now in Spanish and Portuguese, hopefully, to get some folks from on your site as well to do some meetups in Russian. Looking forward to that. The first thing I need to learn in Russian is Hi, my name is Bart. I'm a stupid American who doesn't speak Russian. Rule number one, but yeah, that's kind of how I got in here. And since then, just been super enthused by all the different things that are happening. really embracing the open source mentality, meaning folks are the CNC F as well. So just really happy to be here.

**Matt Yonkovit:**  
Okay, well, it's interesting that you bring up religion studies and religious studies as your background. You know, a lot of what we do in open source has a lot of, I mean, I know like, I don't want to offend people, but it has a lot of religious overtones, almost, if you look at a lot of religions, they tend to be focused on helping people and trying to bring people together and bring together that that community aspect. And there’s this kind of argument that's, that's been going on around the open source where people have been trying to turn it into a business model. And that's something that's, that's really interesting. And it's something that I've kind of thought about quite a bit because when you look at, like, open source as a business model, it's kind of like taking religion as a business model. And you end up with those televangelists who I don't know, if there's a lot of, like, love for most of those televangelists like, send us you know, $500 and we'll pray away or affliction or whatever, in, in, I think that, from an open source perspective, a lot of people who are very passionate in the community are here to, to give up their time to give up their efforts to help make things better in the ecosystem, right, and they want to share, they want to share their knowledge, they want to share their, their know how they want to learn from other people, the best people that I've ever met are in the open source community. Right. And, and I think that that's where you build these relationships, and everybody you might argue it's like a big family, right? You might argue with one another once in a while about, which library is better than another, or which database is superior or not superior. I mean, like, there are arguments, but there's a camaraderie that exists. And it's, it's very much like being part of that kind of religious type movement, much more so than it is a business movement, right? From a business perspective. When you're in a business, you're there to make money. And when you know, it's time to move on, you go to another business and make money and a lot of the people who are in the open source space, keep that philosophy and try to keep open and try to help you know, their colleagues, the community. And that's why a lot of people, the open source base make such great not only contributors but team members,

**Bart Farrell:** 
I can put it, I couldn't agree more. And I think like you said that sort of spirit that you know, that if when the business comes first, for me, I would even say that you can smell it. And you can see it coming from a mile away, when people are really putting community first when they're putting problem-solving first, when and breaking down barriers as well to you know, I mean, how many people from different countries? Are you in touch with me every weekend, the same thing with me now. And it's really, it's extremely exciting to see that despite all the differences of language, the political differences, all these different things, that when there is a true commitment to like, No, we're going to be transparent. And in the same way that I may be helping you improve. Tomorrow, you're going to be doing the same thing for me, really the philosophy of paying it forward. And we can say it is in giving that we receive, that's been like, really extremely motivating. For me, it's something that I, unfortunately, hadn't had as much experience with before. So I think you know, that now, you can say no one is more fanatic than a convert, right. But I would say that I really feel like I've been plugged in very quickly. Everyone's been extremely welcoming, extremely welcoming to the fact as well to of that my background isn't so technical. You know that I have studied a mixture of philosophy, history, sociology, psychology, and things of that nature. But people see that, like, No, you definitely have a part to play here as well, like, you'll those are some skills that I might miss this might not necessarily have. So really looking for the balance in these teams. And like you said, a philosophical approach where it's like, this is the way we're going to do things. And those are some principles that are non-negotiable. And I find that really, really admirable.

**Matt Yonkovit:**  
Yeah, and if you look at a lot of open source contributors, you don't have to be encoder to contribute, in that’s what makes it so unique. Right? It makes it so open so you can contribute by giving a tutorial telling someone how you came to the community how like, doing translation on dogs doing grammar checks. You know we used to have, I believe it was Julian cash, who is a photographer who used to come to all the MySQL conferences to take photos. Right. You know, and so there are different roles for different people to play. And that's what makes it kind of interesting and cool, right? It's people getting together to work for a more common good or a common goal, which generally is how do we solve these problems? How do we solve these real-world things? And yeah, these things are the digital space. But it isn't limited to the digital space, I've talked to the teams that I've led in the past about how impactful what they do is, and here's the thing you don't realize especially from an open source contributor perspective, is you might fix a bug, that particular bug might have prevented a crash at a particular company, that particular company might have service insurance providers, which keep the hospitals running, which then all of a sudden, like, you start to see this, like six degrees away. And the impact that a small tiny contribution can make is massive. And I think that's something that we often overlook, right? Are we often overlook that. It doesn't take a big, big thing to make a huge impact.

**Bart Farrell:**  
Absolutely. And I'm completely on the same page. And I was just talking to somebody actually, well, two things is that like you said, being able to jump in about all the different things you can do in terms of contributing. I started three weeks ago, tomorrow in my third meeting in the contributor experience STG within CF. And once again, extremely welcoming. And the very first day was like, alright, we need someone to interview someone who's quite important in the Oversight Committee, or the tech Oversight Committee, and has been on the governing board has done a lot of different things. And we're six people in the room, and everyone else is like kind of busy, put in my head, I was like, I'll do it. And so I just interviewed her today. And it just like, I can't believe how quickly it accelerated this is but it's like, if you're willing to do it, you can do it. Like you said, translating documents. I've been living in Spain for nine years. So my Spanish is pretty good. And I'm really excited about doing meetups and other languages are translating documents. And then what you were saying about the impact, it was actually someone from Percona, Rick Vasquez who told me a while ago, he was like it nowadays, every company is a tech company. It's not like in 1992, where we had some people out there banging away and, and that they were kind of unseen. Nowadays, as you said, tech permeates everything. So in every hospital, in every school in every senior care facility, we can obviously talk about what's going on right now with the pandemic. But in so many other instances, like those impacts, although they might not be visible, are still tangible in the sense of the value that is creating the difference are making. So I think it's at that, for me is very, very inspiring.

**Matt Yonkovit:**  
Well, and you don't need to look any further than when a major provider has an outage. Right? So if Google has an outage, how many businesses grind to a halt. If AWS has an outage, how many businesses grind to a halt. And this isn't just a cloud provider thing you've got outages that are caused by you know, malware, and you've got outages that are caused by just physical circumstances hey the power went out, and they ran out of juice and the generators that there's, there are so many ways that you can actually see some of that impact, it's really powerful. And it's inspiring because even the smallest contribution can help save quite a bit of time, money, effort, and even lives in a lot of cases. Right. And I think that's where I think we sometimes lose sight of that fact. So, so religion aside, right, so we got into a little bit of a religious-philosophical debate. So what are you working on in the community right now? What are some of the exciting things that are happening and moving forward?

**Bart Farrell:**  
So this is good. So in terms of what we're going for here, because it was just earlier today, I was also talking to somebody else, and they're, like like, what's really the objective here is that it's about knowledge sharing, we're trying to empower people to make these things easier, and give people more options, precisely what you're saying about empowering folks that are working with Kubernetes. So that it's not so overwhelming, so that they can have that conversation with teammates with their, with their boss to make suggestions in overall to provide better experiences and better value for their customers and in their companies. So things that we're doing range from, like I said, expanding on to other languages, because once again diversity inclusion in the strictest sense of like, we of course, our primary language is English, we don't want anyone to feel like they don't have a place in our community just because of that. So making things more accessible in other languages so that we can reach out to as many people as possible for sure. In terms of organizing meetups, we're going to be having two meetups every week in March to Meetups every week in April, even three a couple of weeks. We are and the extending out through May and through June, working on resources to help folks that are you know, come from a DBA background to move more into an SRE or DBRE, as you know, thinking about the skill sets, so in terms of training materials and things that can make that transition smoother. And like I said, there this is a, in some ways a community we can say is not in its infancy, because it has grown quite a bit in the last few months. But you know, this is a topic that to be able to catch on. And to be able to find more examples, we can say, at the enterprise level, there's still some work that has to be done to get there. But our objective is, is, like I said, is to take this out, if which once again, going back to the religious thing, we don't want to look like the crazy haggard prophets wild in the desert shouting about something that's coming, say, like, No, this is actually really happening. But when we're finding more and more use cases, which is interesting for me, because where I live, and this is where we can jump into this wonderful hat that I'm wearing, it's not an array. Alright. And this is the traditional hat from the Basque Country where I live in Spain, it's called a chop ALA. And at first, when I started with data on communities, I was like, could I possibly find you know, a local company that's done this. And sure enough, starting to ask around, I did find a local company, that's an industrial company that makes electric locks for cars. And they had been using, they had been using open EBS for and using Container text storage for a while. And so I was really enthusiastic to see like I don't just have to go to Silicon Valley, I don't just have to go to London or tech capitals to find use cases. But you know, my own backyard. So that's been really, really good. So what we're trying to do is, like I said, is make as much noise as possible, get more folks to come forward and say, Hey, this is how we've done it. These are the problems we've encountered the things that have worked. And so like I said, these conversations get easier and more commonplace.

**Matt Yonkovit:**  
Yeah, no, I mean, that’s great. And when you're talking about, like the meetups that are coming up, what level are these geared towards? Because there's a lot of people who are just starting that Kubernetes journey, I've still heard a lot. A lot of people are worried they're scared about is Kubernetes ready for database workloads. Can we put major applications on there? What kind of things can they expect to learn if they attend some of these, this good?

**Bart Farrell:**    
You'll because and this is a big thing as well, too, is like making it clear, like who is this for? Obviously, we want you always want to say you want to have something for everybody. But certainly and something that I personally have tried to be insistent on is like getting you know, imagining someone who's literally starting from scratch starting from zero, so no one should have to feel embarrassed about what they don't know, just know that they're in a space where they can have access to learn from people that do have experience. So one of the things that that we do as well, too, and every meetup because of that, because generally it's our target SRE is DevOps DBAsdevelopers as well, people that are interested in, in infrastructure, chaos engineering. And because we're talking about outages earlier, that's an interesting topic to people also that are more from the security background. So he gets there if Kubernetes is a big topic, and we say data on top of it while it's got enormous so we try to hit as many different angles as possible, what different kinds of meetups, we've had meetups about networking, we've had multiple meetings about storage, about data, gravity, about data resilience, about data streaming using Kafka. About on to this week, we had one about policy, and you know, about de to Kubernetes, about you know, that Kubernetes out of the box comes with certain things. But another thing as well to this is really good, is that one thing is the technical aspect, but something we always try to include there is what kind of a culture do you need in your company? What kind of mindset do you need to be having. And what a lot of people will say that are really top pros is that you're going to have to be patient, you're gonna have to expect some trial and error. Don't worry, this is a process, don't give up after you know, the first try. And you got to find a solution that works with your company based on your technological stack. I saw this in the company that I was working out because you know, running to the cloud doesn't just mean signing off a bunch of checks for Azure, or AWS, or Google Cloud provider, Google Cloud Platform, sorry, you have to, you really got to be thinking about what are the necessary steps culturally speaking, to have cost control, like, as I mentioned earlier, about the policy about security because they say it takes 10 minutes before containers, start getting attacked, all those different things that have to come into it. So that's why in a lot of ways where we're going for right now is to get as many different angles as possible so that we get all those topics out in the open and then from there can kind of narrow things down and standardize things a little bit more.

**Matt Yonkovit:**  
Okay, so people can expect to learn quite a bit you know, through these different sessions and you'll have different sessions about different topics, but you know, the commonality that goes through all of them is your rap career and your ability to provide lyrics and drop a beat on those topics.

**Bart Farrell:**  
This is also true and I'm glad you mentioned that I'm it to things that we've had since the very beginning with everything that I've done with previous events and things like that is that I work with a guy named Arthur, who's an amazing artist and does visual thinking. So during every meetup and the thing is in his English isn't very good. He speaks Spanish and Basque very well, but His English is not so good. And so while we're doing the meetups, all we kind of agree on some things previously, but he's drawing like it’ll live and direct exactly what's going on and what the speakers mentioned. So we finish every meetup then with a nice visual representation of like topics that have been covered, which also then makes it more accessible for some people that likesome people are more visual learners. And some people you know, are better at listening and things like that. So we want to give as many different opportunities for people to learn. And then the thing about the rack thing is that I've always, I've played music since I was a kid, I start with piano, and then I moved to drums when I was 12. And I started playing guitar when I was 18, and bass, and had always wanted to make hip hop beats since I was a teenager, I would say, about six years ago, without my wife knowing I bought in an NPC to start making beats normally have it right next to my computer. And anyway, so then since then, I've been making hip-hop beats. And once I started getting the community, I was like, there's gonna have to be a time to do this. And so at first, I was doing it more just like a spoken word without beads, but then some people are like it'd be a lot better if you did it with beads. And I'm glad that I took that comment to heart. So since then, after every meetup we with original music, and obviously with original lyrics that we kind of tailor to what the speaker has been talking about. We do it as a way of saying thanks. And also, I guess, in my own way, trying to synthesize some of these concepts. I don't know how much people might actually get out of it. But if some person learns something, or gets more enthusiastic about this, or feels that our community is different because of it, then mission accomplished. Say, it's a lot of fun.

**Matt Yonkovit:**  
So in other words, I might get a theme song.

**Bart Farrell:**    
Oh, I mean, I think is I was actually thinking about before I got on here, it's like what? We've got, yeah, it's been sampled many times, the James Brown song, paid the cost to be the boss ties in pretty well with the Hawks. So yeah, so yeah, that might have to come in there. Yeah.

**Matt Yonkovit:**  
Yeah. I mean there are so many different angles, you know? Well, anyway, I'll just, I'll just let you noodle on that. Okay. Because duly noted, it's, it's the theme song side of things. So if people want to get involved in the community, how do they get involved?

**Bart Farrell:**    
Really easy. We're on Slack, we're on Twitter, we're on LinkedIn, people can contact me directly. And seriously, I insist is that it doesn't matter if you’re a battle-tested practitioner that's got10 years under your belt, working with databases and all kinds of crazy stuff. Or if you're someone who's just curious, in the same way, once again, is that everyone has a place everyone has a because the most beginner question, there's probably somebody else out there who has the same question. Maybe they're a little bit shy, or they're or they're from another country English isn't their first language, and they're going to be grateful that somebody else got that question out there. And the person who's going to answer the question is also going to feel good because they're giving back so like I said, there's no shuts no such thing as a stupid question only stupid silences. So like I said, we're, we're pretty, we're pretty easy to find in those principal areas. And, and like I said, we're very, very excited about growing, we're very open to possibilities. We're working with artists as well to once again, not just one that we have this doing graphic recording, but other folks out there that I'm finding on on Twitter that maybe haven't had a space to show off their art, maybe they’re just an amateur artist who's who does this in their spare time. But it's like, we can find ways to mix this in. Because I think the more that when you visualize things, you create another reality rather than just the one that you might be looking at in terms of code or things like that in a more traditional way. And, and what's something that I've learned, the more that I've been around having friends that are programmers that are also musicians that are also artists, and they insist on the amount of creativity that's also involved in all this. So I think it's it's a really fun way to mix these things. Food will, I guess, be the next challenge. But talking about you know, theme songs and stuff like that, I wanted to ask you, can you tell us how old that hat is? Where you get it? What does it mean to you?

**Matt Yonkovit:** 
This hat is actually not that old. It was designed to look old. Ah, well, yes. Just yeah. Yeah. So the hat thing actually has a store. Okay, like so the hat thing started years ago. Okay. And I got my hat box and I will pull my hatbox out. Yeah, so this is my hatbox. And you can see in the hatbox are several hats. Now, one of these hats or interests is several years ago and I'm going to find the right arm because it's important. We were in California at a conference Percona live and we did an event. So the event was I took everyone to Fry's Electronics. I don't know.

**Bart Farrell:**  
Yeah, but recently saw Twitter Rest in peace, right? 

**Matt Yonkovit:**  
Yes, yes. They just closed down. So yeah, so I took my team. So it was the professional services team at Percona. Over to Fry's gave them all $1,000 and said, build the fastest server you can build. And the winners got this hat. Ah, okay. And so this particular hat then became a calling card. So I actually have a poster, it's on the other side of the desk, I won't grab it. But it was that you know that the next year after wearing this hat, Herb was like, Oh, my God, it's awesome. You know, with a hat, it became the cult of the Propellerhead. So come join the cult of the Propellerhead. And people would stop and get selfies with me and things. And then the year after that, we had Steve Wozniak as a speaker, and I was wearing this and he gave me a whole thing on like, how I should automate this and put solar panels on it and everything else. And then the year after Bill Nye was there, and Bill Nye x hat. Oh, that's legendary. Yeah. And so I'm like, I wear the hat for several years in a row. I didn't wear the hat the next year, and everyone was like, Where's your hat? Where's your head? Where's your hat? The next year? Where's your hat? Where's your like I don't need always need to wear a hat. So that someone bought another hat, so I could wear it. And then everyone know that and they would follow me around to do this. So I started to expand from wearing just this hat because I thought this was a little too focused. So I got all these other hats. I get a hat for every occasion. You know, so if I'm going to talk Postgres, I've got the, of course, the elephant hat. Ohbecausethe Postgres elephant. So I do have that. And if I'm going to talk, MySQL, I've actually got two MySQL hats. Unfortunately, one size does not fit all. So so this dolphin actually doesn't fit very well on my large head.

**Bart Farrell:**
Yeah, but it's extremely charming. So what it lacks, yes. 

**Matt Yonkovit:**  
Yeah, I got another dolphin hat. That's a lot better in here. So this one tends to be my go-to for the dolphins. Ah, yeah. Okay. Right. And so this one fits a little better. I also have a MariaDB hat. I have a Chicken Hat. I got a moose hat. I've got a hat for every occasion. Right. 

**Bart Farrell:** 
But this is one that you're wearing. I'm really sorry. But like, is that what logo is that?

**Matt Yonkovit:**   
So this is the legendary Cleveland Browns, football team.

**Bart Farrell:**
Okay. So all right, what West West Coast ignorance and it's okay.

**Matt Yonkovit:**  
It's the older logo. Yes. Sir, he just was gonna tell me the roster for the browns. I don't really need to know that. Sorry. You know, the recording here will capture off. But so yeah, so I like the Cleveland Browns. I actually moved to Cleveland, the year that the Browns moved out of town and moved to Baltimore. And then they came back two years later, and I was in Cleveland. So I was there like in the new inception of the Cleveland Browns. And then they lost consistently for you know, 20 years. made one playoff had like 30 like get it that the rest is history. But I have always worn Browns garb. So and so it's just a thing.

**Bart Farrell:**
No, it's good. It's good. It's a good habit. And it suits you. So yeah. And I definitely thought it would have been like, Oh, I got this hat. You know, like 25-30 years ago, and uh, no, no, no, it's not that old. 

**Matt Yonkovit:** 
I think it's, it's, I think it's a few years. You know, it was one of these things that I saw it on clearance. And I was like, Oh, wow, that looks pretty cool. Yeah. But I do have the official hos hat here too, which I can switch over to which some people prefer the hos hat.

**Bart Farrell:**  
And the thing is, I learned from a cowboy friend once in high school about the quality of those hats. It's measured in beavers there's like a five beaver, three beavers. Anyway,

**Matt Yonkovit:**  
I have never heard.

**Bart Farrell:**  
I've heard that. Yeah, I'll have to. I'll have to also look that up. Um, yeah, no, but anyway, but it's the point is it's a nice ad. 

**Matt Yonkovit:**  
Well, there you go. There's the story of the hats now. It is forever burned in the memory of everyone who watches this YouTube video?

**Bart Farrell:** 
Yeah, like I said, No, no, yeah. It's like a 3x beaver or something like that. Anyway, walked off to look that up on there. I know. The point is as I said, it's too easy to say you are truly a man of many hats. Do you know how many hats you have?

**Matt Yonkovit:**   
Oh, probably like, several 100, like, my closet is like stack, I only keep the, like the ones that I need to quickly change. Likelike, if I'm gonna be talking with someone, and it's like, we're gonna talk post-Chris, ah I could I could put the post-Chris hat on and I can get a chuckle people will.

**Bart Farrell:**  
But that's the thing though, as well is that once again is that I think that that's the thing is that if you're if you bring that element of humor and calms people down and makes people more comfortable, I think it just, it's like I said, the same ways. Like, for me with the RAPs or music or things like that, it's like me going out there and putting myself out there makes other people right, then I'm happy to do it, if that's what it takes, Oh, please, I can do it all day. 

**Matt Yonkovit:** 
Well, and that's the thing, right? Like, you have to be welcoming, you have to be able to make fun of yourself, you have to be able to really not be ashamed of the things that you like, or you know, the things that you know, you're passionate about. And as you go when you talk with folks, and you know, if you can get them to do a chuckle if you can get them to, like, want to take a selfie with you, I mean, I've got, I've got hundreds, if not 1000s of you no selfies with people wearing funny hats, or doing funny things with that. So, it creates that personal connection, which is always good.

**Bart Farrell:**  
Yeah, it's the same thing. Another thing as well, too, that I like to mix in the meetups is finding out what people like to do in their free time, or what their hobbies are things like that, and then how we can relate that to tech, like when we had alkyne on, um who's a master sailor than spending like half of his life at sea, like, so how can we connect these things to Vitesse, and so getting him to mix those two things together. For me, it just, it just like it's a big one up on the learning experience, because you, you put a filter on it with something else that the person's passionate about, they're an expert on, and they're like, No, I really get what you're talking about. So I find I find that to be very, I don't know, very, very exciting.

**Matt Yonkovit:**  
Yeah, no, and I mean, yeah, it's about making the connections, right. And that's really what the community is all about is being connected with one another understanding that while we're all differentб we do have a lot of commonalities, and making sure that we understand one another. So, so far, I'll give you the final word, or the final question, or the final, whatever you want.

**Bart Farrell:**   
Oh, wow, that's kind of a lot of responsibility. Just glad it's not on my shoulders.  So, um, I know, man, that's I can take, I can probably think of three or four. I guess the final thing is, I got to get back here. This is a really good space to be in, just insists that I'm, I'm open to talking to anybody if they have anything that they would like to contribute feedback as well, seriously, some of one of the best things that people can do is tell you what not to do. Or say, Hey, have you thought about trying this? Like I said, our community can always learn it's a insist on openness. The worst thing that can happen is say, That's a great idea. Maybe right, not now is the time or let me find a way that we could adapt that. So I just really want people to be to I want to insist on the openness on being approachable. And that I hope to have as many conversations with as many people from as many different places to help us keep growing and enrich our community.

**Matt Yonkovit:**  
Great, great to hear. And we'll leave the details for the community Bart on aright after this recording ends. So if you want to reach out to Bart, or anybody in the community, you'll have details on how to do and art. Thank you for hanging out today. I appreciate the time you spent with us and look forward to connecting again. I tip my hat to you, sir. Good one. 

Wow, what a great episode that was. We really appreciate you coming in and checking it out. We hope that you love open source as much as we do. If you like this video, go ahead and subscribe to us on the YouTube channel. Follow us on Facebook, Twitter, Instagram, and LinkedIn. And of course, tune into next week's episode. We really appreciate you coming and talking open source with us.



