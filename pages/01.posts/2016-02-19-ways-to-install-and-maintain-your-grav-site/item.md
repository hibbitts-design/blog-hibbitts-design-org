---
title: '4 Different Ways to Install and Maintain Your Grav Site'
published: true
date: '19-02-2016 00:00'
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': '4 Ways to Install and Maintain Your Grav Site'
    'twitter:description': 'Four approaches of installing and maintaining your Grav site, ranging from a quick Web only install to on-going automatic deployments of a local Grav site to the Web.'
    'twitter:image': 'http://hibbittsdesign.org/blog/posts/2016-02-19-ways-to-install-and-maintain-your-grav-site/gravadmin.png'
    'og:title': '4 Different Ways to Install and Maintain Your Grav Site'
    'og:type': website
    'og:url': 'http://hibbittsdesign.org/blog/posts/2016-02-19-ways-to-install-and-maintain-your-grav-site'
    'og:image': 'http://hibbittsdesign.org/blog/posts/2016-02-19-ways-to-install-and-maintain-your-grav-site/gravadmin.png'
taxonomy:
    category: blog
    tag:
        - GravCMS
        - FlatFileCMS
        - MAMP
---

After my first [Grav CMS for Educators Workshop](../2016-02-10-grav-cms-for-educators-workshop-resources) it became apparent I should provide a wider range of options for how Web-savvy instructors can install and set up the flat-file CMS [Grav](getgrav.org), especially when using my ready-to-run [Course Hub package](../2016-02-12-grav-course-companion-getting-started-guide).

===

So, here are four options for installing and maintaining a Grav site:

## 1) Web Only
Install Grav on a Web server and maintain the site using the Admin Panel, and when needed an FTP text file editor.

_While this is the quickest way to get a Grav site up and running, this approach means that all development is performed on a live website (requiring user authentication)._

## 2) Desktop and Web server (one-time deployment)
Develop the Grav site on your desktop using [MAMP](https://www.mamp.info/), and then deploy the entire site folder to a Web server using an FTP app once the site design is complete. Use the Admin Panel to then maintain the site as needed.

_Educators can safely develop and refine their Grav site on their own computer, and once ready for the start of term deploy the site using an FTP app. During the term only page editing is done on the live website (requiring user authentication). If you want to periodically deploy your site during development, I recommend using [Cyberduck](https://cyberduck.io/?l=en)'s FTP app which includes a ['Synchronize' feature](https://trac.cyberduck.io/wiki/help/en/howto/sync)._

For a step-by-step guide to installing MAMP locally for use with Grav, read the article [Running Grav Locally with MAMP](http://hibbittsdesign.org/blog/posts/running-grav-locally-with-mamp).

## 3) Desktop and Web server (with on-going automatic deployments)

Both of the following approaches use [Git](https://git-scm.com/), and will require Git running on your Web server. While there are many benefits of using Git when developing a website, the most crucial one is that it provides very fine control over what (and when) changes are pushed to your live website.

### Private Git Repository
Install and maintain the Grav site on your desktop with MAMP and then use [GitHub Desktop](https://desktop.github.com/) to quickly sync the site to a private Git repository service as needed for later deployment. If you are looking for a free option to start with, [Beanstalk](http://beanstalkapp.com/) offers a one user private project plan with 100MB of storage and includes automatic site deployment to an FTP Web server.

_With a single press of a button, an educator can quickly deploy any updates of their local Grav site to a Web server. Any text editor can also be used to directly modify Grav files locally, as well as the Admin Panel with user authentication._

### Public (Collaborative) Git Repository
Install and maintain the Grav site on your desktop with MAMP and then use GitHub Desktop to quickly sync the site to a public [GitHub](https://github.com/) repository (free public projects plan) as needed. Updates are automatically deployed to your FTP Web server via a deployment service and 'edit this page' links (via GitHub) can be easily included on site pages (provided with several Grav [skeleton packages](https://www.getgrav.org/downloads/skeletons), including Course Hub and RTFM).

_The use of a public GitHub repository is my preferred approach, as in addition to quick automatic deployment of site updates all course materials are public and course participants can collaborate on both the content and behavior of the site._

You can view a step-by-step guide to set up Grav with GitHub in the article [Using Grav with GitHub Desktop (and Deploy)](../using-grav-with-github-and-deploy).

If you are comfortable with the command line of Git, you might also want to check out these two super informative articles on the Grav website:
* [Grav Development with GitHub - Part 1](https://getgrav.org/blog/developing-with-github-part-1)
* [Grav Development with GitHub - Part 2](https://getgrav.org/blog/developing-with-github-part-2)
