---
title: 'Getting the Grav Course Hub Up and Running'
published: false
date: '12-02-2016 00:00'
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': 'Grav Course Hub Getting Started Guide'
    'twitter:description': 'All you need to know to get started with the open source Grav CMS Course Hub skeleton package.'
    'twitter:image': 'http://hibbittsdesign.org/blog/posts/2016-02-12-grav-course-hub-getting-started-guide/screenshot.jpg'
taxonomy:
    category: blog
    tag:
        - GravCMS
        - Documentation
---

This is a brief guide to help educators use the [Grav Course Hub](https://github.com/hibbitts-design/grav-skeleton-course-hub) as an open and collaborative multi-device partner for their LMS. In other words, to '[flip'](../2015-10-20-flipped-lms-defined) it good!  

![Grav Course Hub Screenshot](screenshot-2.jpg)

===

! This guide has been updated to reflect that the [Git Sync plugin](../2016-12-22-touchdown-seamless-2-way-syncing-arrives-for-grav) is now included with the Grav Course Hub.

**Table of Contents**  
[Course Hub Overview](#course-hub-overview)  
[Flipping your LMS with Grav](#flipping-your-lms-with-grav)  
[Installing the Course Hub](#installing-the-course-hub)  
[Working with Grav](#working-with-grav)  
[Using Git and GitHub Desktop](#using-git-and-github-desktop)  
[Setting Up a Course in Grav Course Hub](#setting-up-a-course)  

## Course Hub Overview
The Course Hub skeleton is intended to accompany a face-to-face, blended or fully online university course. It supports a [flipped-LMS approach](../2015-12-18-flipped-lms-using-an-open-and-collaborative-platform) using the modern flat-file (no database) Grav CMS as an open and collaborative Web platform.

Can't wait to see the flipped LMS approach in action? Explore a mid-term snapshot of the [SFU CMPT-363 Grav Course Hub](http://paulhibbitts.net/grav/cmpt-363-163-demo/), partnered with the [Canvas LMS](https://www.canvaslms.com/).    

### Course Hub Features
* A complete ready-to-run Grav package ([Source on GitHub](https://github.com/hibbitts-design/grav-skeleton-course-hub))
* Blog-format, with 'featured' (sticky) posts
* [Single course](http://hibbittsdesign.org/demo/grav-course-hub-bootstrap/) per Hub, [multiple courses](http://hibbittsdesign.org/demo/grav-multi-course-blog-hub/) per Hub or even [multiple course sub-sites](http://hibbittsdesign.org/demo/grav-multi-course-pages-hub/) (blog + multiple pages per course) per Hub
* Optional important reminders & class preparations areas
* Hub pages can be easily added/removed/changed
* Uses [Markdown](https://daringfireball.net/projects/markdown/) for streamlined cross-platform content
* Image header area above Hub navigation bar
* Sidebar is a simple markdown file, which can also contain HTML
* URL flag to only display page content (for display within LMS). For example, [http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/onlydisplaypagecontent:true](http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/onlydisplaypagecontent:true)
* Creative Commons (CC) License picker
* External links are automatically opened in a new Tab/Window
* Built-in support for Git Sync plugin for 'set-and-forget' syncing to GitHub or GitLab for collaborative site editing
* Since everything is built with Grav it can be _entirely_ customized

### Required Technical Skills
* Markdown or HTML basics
* Understanding folder hierarchies (i.e. relative links)
* Webserver access
* GitHub, GitLab, etc. working knowledge (recommended)

## Flipping your LMS with Grav
### What is a Flipped LMS?
A flipped LMS approach is where an open platform, in the control of course participants,
serves as an alternative front-end to the institutional LMS.

![Flipped-LMS approach](flipped-lms.png)  
_Figure 2. Flipped-LMS approach._

### Why Flip your LMS?
* To support pedagogical goals unmet by current LMS/platform
* To deliver a better student (and facilitator) experience
* To increase capability of access, sharing and collaboration

### Why Use a Modern Flat-file CMS?
As an open source modern flat-file CMS, Grav offers a distinct set of advantages to Web-savvy educators looking to move beyond their institutional LMS:
* Modern means...
  * Use of current standards (i.e. Markdown, Twig, YAML, etc.)
  * Modular/customizable content chunks (i.e. reuse of content)
  * Further separation of content (i.e. files) from presentation
* Flat-file means...
  * No database means less (or no) IT involvement needed
  * Content stored in text files rather than in a database
  * In many cases, this translates into faster page access times
  * Increased portability, as moving a site now only requires simply copying files to another location
  * Takes full advantage of the collaborative ecosystem now available (i.e. GitHub, GitLab, etc.)

Want to learn more about flipping your LMS with an open and collaborative platform such as Grav? Explore more visualizations in the article [Flipped-LMS Approach Using an Open and Collaborative Web Platform](http://hibbittsdesign.org/blog/posts/2015-12-18-flipped-lms-using-an-open-and-collaborative-platform)

## Installing the Course Hub
### Web Install
**Pre-flight Checklist**  
1. Confirm Webserver PHP version (PHP 5.5.9 or higher)
1. Git (v. 1.7.1 or higher) is available on Webserver
1. Webserver login credentials (username and password)

**Installation Steps**  
1. Download the ready-to-run [Course Hub Skeleton Package](../../downloads/grav-skeleton-course-hub-site.zip) ([GitHub Repo](https://github.com/hibbitts-design/grav-skeleton-course-hub))  
1. Unzip the package onto your desktop
1. Copy the _entire_ Grav Course Hub folder to your Webserver
1. Point your browser to the Webserver folder
1. Create your site administrator account when prompted
1. And you're Grav Course Hub is now up and running (press the <i class="fa fa-arrow-circle-right"></i> icon in the Admin Panel to preview site)

### Git Sync Configuration
On the far-right of your site menubar there will be a reminder displayed to complete the two steps to enable GitHub/GitLab syncing and editing of your site content. First tap on the ```Setup Git Sync Plugin (Step 1 of 2)``` menubar link, complete the displayed setup wizard, then return to viewing your site and tap the ```Setup Edit Page in Git Link (Step of 2)``` menubar link and provide the base URL to your created Git repository.

If you would prefer to not use Git Sync with your Course Hub, in your Admin Panel go to the ```Site``` tab on the ```Configuration``` page and set the ```Display of Edit Page Link``` option to ```None``` and then tap ```Save```.

## Git Sync Configuration Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/6SWdIK6N-C0" frameborder="0" allowfullscreen></iframe>
Video 1. Course Hub Setup with GitHub Editing._

## Working with Grav
Now that the Grav Course Hub is up and running you are ready to start working with Grav! To learn how Grav is organized, and how to add and edit pages, read the [Grav Basic Tutorial](https://learn.getgrav.org/basics/basic-tutorial).

You can view the all of the official Grav documentation at [learn.grav.org](http://learn.getgrav.org/). If you are looking for additional help check out the [Getting Help](http://learn.getgrav.org/basics/getting-help) section.

### Grav for Educators Workshop Slides

If you are new to Grav, you might find these workshop slides helpful:
<div class="video-responsive video-responsive-4-3"><iframe src="//slides.com/paulhibbitts/grav-cms-for-educators/embed" width="576" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe></div>

## Using Git and GitHub Desktop
* [Git for Designers](http://danielfos.co/notes/git-for-designers)  
* [Getting your project on GitHub](https://guides.github.com/introduction/getting-your-project-on-github/)  
* [Introduction to GitHub](https://github.github.com/on-demand/intro-to-github/)

## Setting up a Course
For details about configuring and further customizing the Grav Course Hub read [Setting Up a Course in the Grav Course Hub](../2016-07-18-setting-up-your-grav-course-hub).

<br>
Suggestion or corrections to this guide? [<i class="fa fa-github" aria-hidden="true"></i> Edit this Page on GitHub](https://github.com/hibbitts-design/hibbitts-design-org-blog/edit/master/posts/2016-02-12-grav-course-hub-getting-started-guide/post.md)
<br>
