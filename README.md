# space-theme

To check your version of Hugo, run:

hugo version
This will output the currently installed version of Hugo. Make sure you see /extended after the version number, for example Hugo Static Site Generator v0.51/extended darwin/amd64 BuildDate: unknown You do not need to use version v0.51 specifically, you can use any version of Hugo above 0.51. It just needs to have the /extended part

Create a new Hugo site 
hugo new site mynewsite
This will create a fresh Hugo site in the folder mynewsite.

Install theme 
Copy or git clone this theme into the sites themes folder mynewsite/themes

Install with Git 
cd mynewsite
git clone https://github.com/fajarbaiz/hugo-space-theme.git && cd hugo-space-theme
You can download the .zip file

baseURL = "/"
themesDir = "themes"
theme = "hugo-space-theme"

hugo
For local development run Hugo’s built-in local server.

hugo server
Now enter localhost:1313 in the address bar of your browser.

# License 
If you fork or copy this theme the LICENSE file and the copyright notice on line 3 (where I am listed as the author) must not be changed. You cannot just replace the copyright line with your own name. Attribution in your README.md or on your site is also welcome but not required.
