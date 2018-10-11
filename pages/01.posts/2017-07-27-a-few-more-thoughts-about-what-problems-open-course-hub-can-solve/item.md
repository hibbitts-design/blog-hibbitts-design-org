---
title: "A Few More Thoughts About... What Problems Open Course Hub Can Solve"
date: 07/27/2017
published: true
continue_link: false
header_image: false
taxonomy:
    category: blog
    tag:
        - CourseHub
metadata:
    'twitter:card' : summary
    'twitter:site' : @hibbittsdesign
    'twitter:title' : A Few More Thoughts About... What Problems Open Course Hub Can Solve
    'twitter:description' : A list of key problems that Grav Open Course Hub was created to solve, in partnership with your existing Learning Platform.
    'twitter:image': 'http://hibbittsdesign.org/blog/posts/2017-07-27-a-few-more-thoughts-about-what-problems-open-course-hub-can-solve/flipped-lms.png'
---

_I recently [tweeted the key problems Grav Open Course Hub was created to solve](https://twitter.com/hibbittsdesign/status/890281333011824640) for **tech-savvy educators**, and I thought I would share them here:_

1. Pedagogical goals are unmet by the current Learning Platform (e.g. LMS or CMS) alone
2. Student and facilitator experiences, especially multi-device, are below expectations
3. Ability to access, share and collaboratively edit course materials is lacking
4. The creation and (often frequently needed) updating of online course materials is too time consuming
5. Once created, online course materials are difficult to repurpose on different platforms for different contexts
6. Unable to leverage existing Web authoring skills or standards on the current Learning Platform

Let's take a quick look at how the [Grav Open Course Hub](http://learn.hibbittsdesign.org/coursehub) addresses each of these problems:

_**Pedagogical goals are unmet by the current Learning Platform (e.g. LMS or CMS) alone**_  
Since the Course Hub is built with the open source and extensible [Grav CMS](https://getgrav.org/) and an individual instance of Grav is used for each course, tech-savvy educators have virtually no limits to what additional elements they can embed into their own Course Hubs.

_**Student and facilitator experiences, especially multi-device, are below expectations**_  
The two available Course Hub themes (the default theme is built with  [Bootstrap](https://getbootstrap.com/) and the alternative theme is built with [Zurb Foundation](http://foundation.zurb.com/)) are completely responsive, and Grav's speedy performance further enhances multi-device delivery of content.

_**Ability to access, share and collaboratively edit course materials is lacking**_  
Using the [Git Sync Plugin](https://getgrav.org/blog/git-sync-plugin), Grav pages be automatically stored and edited with modern collaborative ecosystem tools such as GitHub, GitLab, and GitBook.

_**The creation and (often frequently needed) updating of online course materials is too time consuming**_  
Once again thanks to the Git Sync Plugin, course hub contributors can synchronize Course Hub content (even including theme files) to their own desktop and use the text editor of their choice to update content. Edits, and pushing updates to a live Course Hub site, can be done in as little as 30 seconds.

_**Once created, online course materials are difficult to repurpose on different platforms for different contexts**_  
Since Grav CMS uses [Markdown](https://en.wikipedia.org/wiki/Markdown), which is rapidly becoming the modern standard for platform-independent markup of content, the opportunities for repurposing content is steadily increasing.

_**Unable to leverage existing Web authoring skills or standards on the current Learning Platform**_  
With Grav CMS built using many of today's best standards (i.e. Markdown, Twig, YAML, etc.) and extensible architecture both educators and students can further shape the Course Hub using their Web authoring skills.

In addition, the Grav Open Course Hub was intentionally designed to work with your existing Learning Platform (by 'flipping' it, where an open platform such as the Grav CMS is in the control of course participants and serves as an alternative front-end to the institutional LMS). This means that instructors can immediately start to address the above problems while still using their existing Learning Platform to store sensitive student data and other course requirements. View this approach in action on my 2016 [CMPT-363 User Interface Design course site](http://paulhibbitts.net/cmpt-363-163-archive/).

![Git Sync Wizard](flipped-lms.png)  
_Figure 1. Flipped LMS approach using Grav Open Course Hub with Git Sync_

So, do these challenges resonate with you? How are you currently solving them? I'd love to hear from you!
