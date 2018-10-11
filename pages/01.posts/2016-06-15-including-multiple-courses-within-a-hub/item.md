---
title: 'Including Multiple Courses Within a Hub'
published: false
date: 06/15/2016
continue_link: true
header_image: false
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': 'Including Multiple Courses Within a Hub'
    'twitter:description': 'A brief overview of the experimental support for multiple courses within a single hub.'
    'twitter:image': 'http://hibbittsdesign.org/blog/posts/2016-06-15-including-multiple-courses-within-a-hub/multi-course-home.png'
taxonomy:
    category: blog
    tag:
        - GravCMS
        - Multi-course
---

Based on some discussions with my fellow educators at the inspirational  [Festival of Learning](https://festival.bccampus.ca/) in Burnaby, BC last week I've added experimental support for multiple courses (i.e. blogs) within one course hub. Don't worry, the code behind the scenes is fully-tested - I am using the term 'experimental' to indicate I am still refining this approach and testing various use cases as I hear of them from other instructors.

With a single hub containing multiple courses you can now selectively not only share content/elements between different pages of one course, but also between one or more courses. And just like a single course hub, all course materials can be shared on GitHub/GitLab for collaborative editing.

===

Ok, let's get started!

Here are the step-by-step instructions needed for creating a course hub to include two related courses:

1. Open the course hub 'pages' folder (located your Grav course hub 'user' folder).

2. Delete the default '03.syllabus' folder. For each course you could either link to an external Syllabus (i.e. located in your LMS) or make a post in each course blog containing the syllabus.

3. Rename your existing '02.resources' folder to '03.resources'. This will be an example global page that will be shared between your example two courses.

4. Duplicate the existing '01.home' folder and name the copied folder '03.course-2'.

5. Rename the '01.home' folder to '02.course-1'.

6. Create a new '01.home' folder and inside it create a text file called 'sidebarpage.md'.

And that is basically it! The 'page' folder ' should now look like this:

```
01. home
02. course-1
03. course-2
04. resources
```
_Figure 1. Structure for a Course Hub with two related courses._

Another example of a Course Hub with multiple courses, each with a single blog page, for each course within the Course Hub:
![Course Hub ```pages``` folder structure for multiple courses, with a single blog page per course ](multi-course-blog.png)  
_Figure 2. Course Hub ```pages``` folder structure for multiple courses, with a single blog page per course._

Multiple pages, including a blog, for each course within the Course Hub is also possible:  
![Course Hub ```pages``` folder structure for multiple courses, with a single blog page per course ](multi-course-pages.png)  
_Figure 3. Course Hub ```pages``` folder structure for multiple courses, with a single blog page per course._

You will also want to modify the site title in the 'site.yaml' file within your '/user/config' folder to something appropriate.

Bonus feature! Each course blog can also contain its own sidebar and header image - simply make a copy of each folder within your 'pages' folder into each course folder.

Want to see a multiple course hub in action? Visit a demo where each course has it's own blog page at [demo.hibbittsdesign.org/grav-multi-course-blog-hub](http://demo.hibbittsdesign.org/grav-multi-course-blog-hub/) and download a ready-to-run skeleton site at [github.com/hibbitts-design/grav-skeleton-multi-course-blog-hub-site](https://github.com/hibbitts-design/grav-skeleton-multi-course-blog-hub-site)

UPDATE: You can also now configure each course within a multiple course hub to have it's own set of pages, including a blog. Visit a demo at [demo.hibbittsdesign.org/grav-multi-course-pages-hub/](http://demo.hibbittsdesign.org/grav-multi-course-pages-hub/) and download a ready-to-run skeleton site with example custom sub-pages and menu at [github.com/hibbitts-design/grav-skeleton-multi-course-pages-hub-site](https://github.com/hibbitts-design/grav-skeleton-multi-course-pages-hub-site). If you have installed the latest version of a Course Hub theme, you can also just copy an example set of pages within your theme's '_demo' folder to your '/user/pages' folder.
