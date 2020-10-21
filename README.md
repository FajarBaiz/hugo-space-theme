![artboard1](static/assets/img/artboard1.png)

## Features
Features in the ori.:

* Simple and easy to customize
* Concentrated on reading and writing (find a Markdown editor then) experience
Mobile-friendly & widescreen-friendly
* Flexible commenting control
Features in this ported version:

* Add Gitalk and Valine intergration.
* Customizable color scheme. (Some bug in original version, fixed.)
* Firefox-friendly. (CSS issue in original version, fixed.)

## Getting started
At the root of your Hugo project, run:

``git submodule add https://github.com/FajarBaiz/hugo-theme-space.git themes/hugo-theme-space``
Next, copy the contents of the exampleSite/config.toml to your site's config.toml. Make sure to read all the comments, as there a few nuances with Hugo themes that require some changes to that file.

The most important change you will need to make to the config.toml is removing this line:

themesDir = "../../" 
It only exists in the example site so that the demo can function properly.

Finally, run:

``hugo server -D``

# DEMO
[https://fajars.space](https://fajars.space)
