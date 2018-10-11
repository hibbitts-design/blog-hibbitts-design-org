---
title: 'Why I (as a Web-savvy Instructor) Chose the Grav CMS'
published: true
date: '03-02-2016 00:00'
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': 'Why I (as a Web-savvy Instructor) Chose the Grav CMS'
    'twitter:description': 'A summary of the reasons why I choose the modern flat-file Grav CMS for my flipped-LMS approach.'
    'twitter:image': 'http://hibbittsdesign.org/blog/posts/2016-02-03-why-I-chose-Grav/gravdotorg.png'
taxonomy:
    category: blog
    tag:
        - GravCMS
---

I came across this tweet today, thanks to the [@getgrav](https://twitter.com/getgrav) Twitter feed:

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Working on a CMS comparison of <a href="https://twitter.com/statamic">@Statamic</a>, <a href="https://twitter.com/getkirby">@GetKirby</a>, <a href="https://twitter.com/craftcms">@CraftCMS</a>, &amp; <a href="https://twitter.com/getgrav">@GetGrav</a>. Any insights you’d like to share? <a href="https://t.co/RZYL4sf0yT">pic.twitter.com/RZYL4sf0yT</a></p>&mdash; Patrick Haney (@notasausage) <a href="https://twitter.com/notasausage/status/694972469300568066">February 3, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

This is something I can definitely speak to, as in fact just over a year ago I tried out each of the above CMSs (and a few others) for use as a new course website platform. Here is a little trip down memory lane...

===

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Exploring some newer CMS&#39;s these days for multi-device educational contexts - most promising are <a href="https://twitter.com/hashtag/CraftCMS?src=hash">#CraftCMS</a>, <a href="https://twitter.com/hashtag/OctoberCMS?src=hash">#OctoberCMS</a>, and no DB <a href="https://twitter.com/hashtag/Statamic?src=hash">#Statamic</a></p>&mdash; Hibbitts Design (@hibbittsdesign) <a href="https://twitter.com/hibbittsdesign/status/539841717914988544">December 2, 2014</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Really digging <a href="https://twitter.com/getgrav">@getgrav</a> as a potential multi-device course companion platform! Modern UX, fast, dynamic, no database, and very pliable.</p>&mdash; Hibbitts Design (@hibbittsdesign) <a href="https://twitter.com/hibbittsdesign/status/543173459313184768">December 11, 2014</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Two more modern CMS&#39;s that I am evaluating for multi-device educational contexts: <a href="https://twitter.com/getgrav">@GetGrav</a> and <a href="https://twitter.com/BoltCM">@BoltCM</a>, which has &#39;resource&#39; content types.</p>&mdash; Hibbitts Design (@hibbittsdesign) <a href="https://twitter.com/hibbittsdesign/status/545648369176023040">December 18, 2014</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

I even went ahead and purchased a single user [Statamic 1.0](http://statamic.com/) license, as there was no free trial available at the time. As you can see from the above, I also checked out [OctoberCMS](https://octobercms.com/) and [Bolt](https://bolt.cm/) during my evaluation phase.

For each CMS I tried to modify either a default site and/or start a new simple project site. I was able to do this with each CMS easily enough, but found the CraftCMS had the most feature-rich editing environment and a very strong modular content approach as well. Statamic was also quite promising initially, but I soon ran into several difficulties including getting the available Foundation theme handling dropdown menus. Overall, I found that things work the easiest for me with OctoberCMS, Kirby, Bolt, and Grav.

All of the above CMSs are also "modern" in general terms, but as I learned more about what a flat-file CMS could specifically provide I decided to focus on that aspect.

_Some key benefits of flat-file CMSs, especially for educators:_
* No database means less (or no) IT involvement needed
* Increased portability, as moving a site now only requires simply copying files to another location
* Takes full advantage of the collaborative ecosystem now available (i.e. GitHub, GitLab, etc.)

Once I decided that a flat-file CMS was the best fit for my needs, then OctoberCMS, [CraftCMS](https://craftcms.com/), and Bolt were all eliminated from the running. I also wanted to use an open source platform, so that then removed Statamic from the running.

So why did I choose [RocketTheme's](http://www.rockettheme.com/) [Grav](https://getgrav.org/) over Kirby given my initial analysis? After a bit of thought, I would say the main reasons were:

* Excellent conceptual/design model
* Markdown/Twig/YAML usage
* Self-contained Skeleton format
* Inherited themes
* Multiple open-source themes suitable for my needs
* Powerful modular content support
* Custom content type definitions
* File editing and/or fully-featured Web editor (which was planned for Grav 1.0)
* Documentation quality (bonus points: it's built with Grav [learn.grav.org](http://learn.getgrav.org/))
* Level of community support/engagement
* Example GitHub integration (which also supports [my current preferred workflow](http://hibbittsdesign.org/blog/posts/using-grav-with-github-and-deploy))

Speed/responsiveness was also an important consideration, but based on my initial experiences Grav and Kirby seems pretty evenly matched on that issue.

It's just over a year later and I am feeling really good about my choice. [Grav v1.0](https://getgrav.org/blog/grav-1.0-released) has now been released, and both its capabilities and the community keep growing. A [public roadmap for Grav in 2016](https://getgrav.org/blog/plans-for-2016) is available which also includes [Gantry 5](http://gantry.org/), RocketTheme's theme framework available on Joomla and soon on Wordpress. From everything that I've seen so far Gantry will bring some really easy-to-use but powerful theme customization features to Grav.

As a side-note, I've also used other platforms such as [WordPress](https://wordpress.com/), [Concrete5](http://www.concrete5.org/), and [Moodle](https://moodle.org/) to create my course hubs in the past, but with Grav I've been able to achieve a much higher level of customization than _ever_ before. With only basic HTML/CSS knowledge, coupled with the incredible ease of use of the [Twig](http://twig.sensiolabs.org/) language, Grav has enabled me to design and deliver much better experiences for my students and fellow educators. I've even been able to create my own open source [Course Hub](https://github.com/hibbitts-design/grav-skeleton-course-hub) project to help other educators get started with Grav, which I plan to also release as a self-contained Grav skeleton package.

Want to read a more detailed overview of Grav? Check out David Walsh's article [Grav: Building Fast and Flexible Websites](https://davidwalsh.name/grav-building-fast-flexible-websites).

I look forward to reading [Patrick's](https://twitter.com/notasausage) CMS comparison article next!
