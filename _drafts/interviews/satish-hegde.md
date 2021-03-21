---
layout: post
title: "Interview with Satish"
published: false
tags: interview
---

<!-- 
The blog has the following structure:
1. What these blog series is about
2. Who is Satish? -- his role and play in wipro
3. What work he has done in open-source
	3.1 gnome
	3.2 expect scripts
4. His move to cloud and kubernetes
	4.1 how did he discover Docker
5. Satish's role as a consumer of open-source
6. His thoughts on open-source and wipro and the things in-between
-->

## what are these blogs and interviews about?

*Aloha*, *Konichiwa*, *Namaste* and *Hi* to everyone reading this blog. The Open Source Community within Wipro is at a niche stage and we are growing each day. The goal is to have an engaged and informed community that maximises the effectiveness of our resources and most importantly, gives our developers a better experience in their journey of contributing to open-source. 

Wipro has been a long time contributor to various open-source projects over the last two decades. The goal of this blog series is to find the champions who lead these open source efforts at Wipro and connect them with you, our readers! We have a bunch of interviews planned and as we go along, we will introduce you to a bunch of really cool people whose journeys will inspire you.

Each blog is accompanied by a video of the interview, which you are welcome to watch, like and comment on. We would definitely want to know what kind of content you would want to watch in and learn from this series. You can tweet at us using the hashtag [#wiproFOSS](https://twitter.com/hashtag/wiproFOSS).

# Introduction

The open-source community is driven by two things: the spirit of collaboration and the spirit of hacking, the willingness to share your knowledge and experiences constitutes collaboration and the urge to experiment, dismantle and make new things constitutes hacking. Our very first interview is with an individual, who embodies both of these ideals.

Satish is a long-time Wiproite. He has been at Wipro since 1995. Throughout, the interview, the thing that stood out the most to us, was the passion and love Satish felt for the technology he worked on. This technology-centric approach, is part of the Wipro culture and I'm very happy to work with people, who encourage this focus on technology. Satish, throughout his long career, has worked on a bunch of things, ranging all the way for Unix development, testing, POSIX standard compliance and cloud.

Innovation and experimentation is the life-blood of a company like Wipro since, the work we do in technology is never-ending. 

Satish joined Wipro 25 years ago and is a veteran here, he started as a test engineer for UNIX platform, since then has successfully carried out various roles of a module lead, test lead, Project Manager, Program Manager for migration, Architect / Consultant. He got the opportunity to learn and work with various platforms/domains/technologies at Wipro like embedded Unix, Telecom, Storage, cloud, containerization, etc. and this inspires him to stay with the Organization & continue the learning.  He has moved into Cloud practice, worked with Docker and finally on Kubernetes.

## The humble beginnings
Satish started in Wipro as a test engineer, his first gig was testing the features for a custom version of an UNIX system. Satish spent much of his time, understanding the basics of UNIX, and also at the same time preparing the documentation ensuring that the programs he was testing were [POSIX](http://www.unix.org/unix98.html) compliant. Later in the interview, Satish highlights how this initial experience with UNIX, later on paved his way to working on kubernetes, as his strong foundation supported him in working on more and more complex projects.

## GNOME

During our interview, Satish shared with us what it was like to use and contribute to open-source a couple of days, ago. Early in his career as a test lead, Satish had the opportunity to work on the GNOME desktop environment. He had been tasked with integrating the GNOME DE with Sun Solaris' UNIX system. As a test module lead, it was Satish's job to lead a team that made sure the changes made by the development team were working with the changes being made by the open-source community to the GNOME code-base. During this assignment, which lasted around 1.5 years, Satish and his team wrote more than 4000 unit tests. Almost all of these tests were contributed back to the GNOME desktop environment.

Back in 2004-2005, GNOME was in its early days, with poor documentation. We can see some of Satish's emails on the GNOME mailing-list, asking for help with documentation.

<a href="https://mail.gnome.org/archives/desktop-devel-list/2002-March/msg00149.html">
![gnome-mailing-list](assets/images/01-satish-hegde/satish-gnome-mailing-list.png)
</a>

Satish shared, how difficult it was to maintain code stability, in those early days. Everytime they would pull code, from the GNOME repository, their own tests and builds would start failing.

However, Satish had more than just these technical challenges to overcome. Satish, shared how all of their work, was shrouded in secrecy. Satish's client had given strict warnings, that no one in the larger community could find out about the work that they were doing on the integration of the two desktop environments, as long as the finished product wasn't ready.

Today, as Satish continues to work for clients on proprietary solutions, he works in an environment that is much more welcoming to open-source, today, there are proper processes in place, that help developers quickly decide whether or not certain open-source tools/libraries in their work.

## Satish and his journey into Kubernetes

**TODO**: need to add something more about the `expect` thingy.
Satish has been using different kinds of open-source tools for almost all of his career, as a testing lead. He relays the one time he used the [`expect`](https://www.tcl.tk/man/expect5.31/expect.1.html) module that uses scripts written in [TCL](https://www.tcl.tk/).

Satish throughout his career, has worked on numerous Linux and Unix-based distros from the popular ones like centOS and Debian to more niche ones like Alpine Linux. The many years, he spent in the Linux ecosystem, helped him develop his problem-solving skills.

In 2016, his manager (enter name of Manager here), introduced Satish to Dockers and containers. He gave Satish an AWS instance and 2 weeks of time, asking him to learn whatever he could and experiment. 2 weeks later, Satish along with his manager, presented a docker-based solution to a client. This is a recurring theme, that we will continue seeing throughout Satish's interview and the many other interview that will happen in the future. There is a culture of pushing people out of their intellectual comfort zones, practiced by Managers at Wipro. In the case, of Satish, time and again, Satish has rised to meet the technical challenges set in front of him by his clients or managers. Whether, it is about learning something new, or achieving a highly complex solution. Satish grows in great depth througout the interview, mentioning all the great work he has done as part of the Cloud Practice, at Wipro.

### How do you think Wipro can benefit from participating in open-source as opposed to just consuming it?
1. Opportunity interact with community leaders/experts & develop skill set in various / new domains, acquire additional knowledge about product/tool for development or enhancement.
2. Becoming Open-source module owner/leader, contribution or maintenance of projects gives international reputation.
3. Leverage Organizational best practices on Product Quality improvements, risks / mitigation approach which helps to improve the quality of open source deliverables.
 
### 	What is your take on Wipro’s position in the open-source space as compared to its competitors? 
1. I think Wipro has Open Source Advisory Service / Consulting for clients who wish to leverage/adapt open source products for their services.
2. As Wipro provide services on various domains/technologies, it should encourage domain/technology experts to contribute actively to the development/maintenance of generic open source software/tools in respective domains. 
3. Leadership in Open Source community with domain skills would help internally for the potential customers, deliver customized pre-owned open-source solutions with speed, agility & cost-effective approach.

## Ideas on creating a full-grown and engaging open-source community within Wipro? 
1. There can be Open Source Practice which actively work with community leaders, contribute to various module development, ownership or maintenance 
2. Active participation in community conferences, speaker sessions on Wipro contributed source/tools.
3. Open-Source practice can participate in Proposal Solutions, provide cost-effective custom solutions  
4. Like DMTS, special recognition for core contributors of Open Source.

<!--
## Satish's work in GNOME project

In 2002, Satish was working on integrating the GNOME desktop environment into Sun Solaris operating system for Sun Microsystems.
He was the testing lead leading a team for more than 10 developers, designing and documenting more than 4000 unit tests during his time working on the GNOME project.

### what was your experience working on integrating an open-source project into a proprietary product?

The Open Source concept was at a very niche stage at the point when Satish was working with the GNOME project. There were clear instructions on no client involvement exposure on any conversations with the GNOME community, a bunch of secrecy was to be maintained however whatever could be given back to the community, needed to be contributed back.

### what were the major technical challenges you faced?

Due to the concept being very new, there was lack of documentation and the project was quite unstable.Builds would break everytime a new code was pulled from the CVS repository.

## Which open-source communities are you a part of? 
 
Satish is not officially associated with any open-source community but used them during various project assignments.
1. GNOME foundation
2. Apache Software foundation
3. Cloud Native Computing Foundation
4. Heard of Drupal, Eclipse or Free Software foundation

## People who helped Satish from various communities

Satish remembers his chance to interact with Ximian (Open Source packaging company – GNOME) through which he was introduced to couple of community leaders on specific modules.
-->
