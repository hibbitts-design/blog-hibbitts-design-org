---
title: "Customizing a Grav Course Hub Theme"
date: 04/18/2016
published: true
continue_link: true
header_image: false
taxonomy:
    category: blog
    tag:
        - Theme
        - GravCMS
metadata:
    'twitter:card' : summary
    'twitter:site' : @hibbittsdesign
    'twitter:title' : Customizing a Grav Course Hub Theme
    'twitter:description' : A look at the options available to visually customize a Grav Course Hub Theme.
---

Like any other Grav theme, both of the included Course Hub themes ('[Course Hub Bones](https://github.com/hibbitts-design/grav-theme-course-hub-bones)' and '[Course Hub Bootstrap](https://github.com/hibbitts-design/grav-theme-course-hub-bootstrap)') can be visually customized using CSS and/or altering their Twig template files. However, if you make changes directly to the Course Hub theme these will be overwritten when that Course Hub theme is updated. So, what to do?

===

The easiest method to customize a Course Hub theme is to use Grav's [theme inheritance](https://learn.getgrav.org/themes/customization#theme-inheritance) feature. However, as the Course Hub Bootstrap theme is actually an inherited theme, the following should be included in your `/user/themes/mytheme/mytheme.yaml` file:

```
streams:
 schemes:
   theme:
     type: ReadOnlyStream
     prefixes:
       '':
       - user/themes/my-theme
       - user/themes/course-hub-bootstrap
       - user/themes/bootstrap
```

While an inherited Grav theme usually only has two theme references (the inherited theme and it's source theme), three theme references are required with the Course Hub Bootstrap theme to ensure all the needed theme elements are available. You will also need to copy the existing Course Hub Bootstrap `/css/custom.css` file into your inherited theme's `css` folder.

For those educators who want to make a lot of customizations, creating an independent child theme is likely the best process. In essence, creating a child theme involves duplicating the folder of an existing theme and then defining the needed unique elements (such as the name) for that theme.

For more information about Grav theme development, check out the Grav [Theme Tutorial](https://learn.getgrav.org/themes/theme-tutorial).
