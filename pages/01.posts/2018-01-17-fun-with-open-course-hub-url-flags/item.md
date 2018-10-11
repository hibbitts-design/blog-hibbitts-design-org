---
title: 'Fun with (URL) Flags'
date: 01/17/2018
continue_link: true
header_image: false
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': 'Fun with Open Course Hub (URL) Flags'
    'twitter:description': 'A look at how the built-in URL flags of Open Course Hub helps better integrate Grav CMS content into existing LMSs'
    'twitter:image': 'http://hibbittsdesign.org/blog/posts/2018-01-17-fun-with-open-course-hub-url-flags/week4-chromeless-summaryonly.png'
taxonomy:
    category: blog
    tag:
        - GravCMS
        - CanvasLMS
        - Moodle
        - Integration
        - URLflags
---

<div class="video-responsive video-responsive-4-3"><iframe src="https://giphy.com/embed/QTwv9aLCaaEgM" width="480" height="271" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div>

The Grav Open Course Hub supports a number of optional URL flags (i.e. parameters) to better support embedding Hub content into other LMSs such as Canvas or Moodle:

`chromeless` - hide all global navigation elements  
`summaryonly` - display the summary of a blog post  
`hidepagetitle` - hide the title of a page  

===

Each URL flag can be added to a URL referencing a specific page of a Grav Open Course Hub site in the format `flagname:true`, for example:  

`yourgravsite.com/chromeless:true`

and multiple flags can be used at once, for example:  

`yourgravsite.com/chromeless:true/hidepagetitle:true`

So, time for some live demos!  

View the standard Open Course Hub homepage:  
[demo.hibbittsdesign.org/grav-course-hub/](http://demo.hibbittsdesign.org/grav-course-hub/)

![Grav Open Course Hub Homepage](home.png)  
_Figure 1. Grav Open Course Hub Homepage._

And now let's view the same page using the `chromeless` URL flag:  
[demo.hibbittsdesign.org/grav-course-hub/chromeless:true](http://demo.hibbittsdesign.org/grav-course-hub/chromeless:true)

![Chromeless Grav Open Course Hub Homepage](home-chromeless.png)  
_Figure 2. Chromeless Grav Open Course Hub homepage._

Getting the idea? Let's continue!  

View Week 4 for an Open Course Hub site:  
[demo.hibbittsdesign.org/grav-course-hub/home/unit-04/](http://demo.hibbittsdesign.org/grav-course-hub/home/unit-04/)

![Grav Open Course Hub Week 4 Page](week4.png)  
_Figure 3. Grav Open Course Hub week 4 page._

Now view the same page using the `chromeless` URL flag:  
[demo.hibbittsdesign.org/grav-course-hub/home/unit-04/chromeless:true](http://demo.hibbittsdesign.org/grav-course-hub/home/unit-04/chromeless:true)

![Chromeless Grav Open Course Hub Week 4 Page](week4-chromeless.png)  
_Figure 4. Chromeless Grav Open Course Hub week 4 page._

You can also hide the page's title, like this:  
[demo.hibbittsdesign.org/grav-course-hub/home/unit-04/chromeless:true/hidepagetitle:true](http://demo.hibbittsdesign.org/grav-course-hub/home/unit-04/chromeless:true/hidepagetitle:true)

![Chromeless Grav Open Course Hub Week 4 Page with Title Hidden](week4-chromeless-nopagetitle.png)  
_Figure 5. Chromeless Grav Open Course Hub week 4 page with title hidden._

And even just display the summary (preview) of the page:  
[demo.hibbittsdesign.org/grav-course-hub/home/unit-04/chromeless:true/hidepagetitle:true/summaryonly:true](http://demo.hibbittsdesign.org/grav-course-hub/home/unit-04/chromeless:true/hidepagetitle:true/summaryonly:true)

![Chromeless Grav Open Course Hub Week 4 Page with Title Hidden and Summary Only](week4-chromeless-summaryonly.png)  
_Figure 6. Chromeless Grav Open Course Hub week 4 page with title hidden and summary only._

Using the above three URL flags it's possible to embed various elements of your Grav Course Hub site into other LMSs, for example [Canvas](https://canvas.sfu.ca/courses/36662) or <a href="http://paulhibbitts.net/moodle/course/view.php?id=2">Moodle</a>.

For detailed instructions, these step-by-step guides might be of interest:
* [Open Course Hub - Integrating Grav with Canvas LMS](http://learn.hibbittsdesign.org/coursehub/integrating-grav-with-canvas-lms)
* [Open Course Hub - Integrating Grav with Moodle](http://learn.hibbittsdesign.org/coursehub/integrating-grav-with-moodle)
