![artboard1](img/artboard1.png)

## 1. Install Hugo
``brew install hugo``

    or

``port install hugo``
    
minimal versi hugo 0.41.0

To check your version of Hugo, run:

``hugo version``

## 2. Create a New Site
``hugo new site myweb``
    The above will create a new Hugo site in a folder named myweb.

## 3. Add a Theme
``cd myweb``

``git init``

``git submodule add https://github.com/fajarbaiz/hugo-space-theme``

Then, add the theme to the site configuration:

``echo 'theme = "ananke"' >> config.toml``

## 4. Add Some Content
``hugo new posts/my-first-post.md`` 

Edit the newly created content file if you want, it will start with something like this:

---
title: "My First Post"
date: 2019-03-26T08:47:11+01:00
draft: true
---

## 5. Start the Hugo server
``hugo server``

Navigate to your new site at http://localhost:1313/.

## 6. Customize the Theme 
Site Configuration
Open up config.toml in a text editor:

baseURL = "https://example.org/"
languageCode = "en-us"
title = "My New Hugo Site"
theme = "space-theme"

# Build static pages
It is simple. Just call:

``hugo -D``

Output will be in ./public/ directory by default (-d/--destination flag to change it, or set publishdir in the config file).

# License 
If you fork or copy this theme the LICENSE file and the copyright notice on line 3 (where I am listed as the author) must not be changed. You cannot just replace the copyright line with your own name. Attribution in your README.md or on your site is also welcome but not required.
