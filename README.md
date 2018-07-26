# uscbiomems.github.io - website of the Biomedical Microsystems Laboratory at USC

custom domain: biomems.usc.edu

website launched 20180725 by Christopher Larson

## development/maintenance notes for future grad students in the lab:

The previous version of the lab website was hosted on USC's servers, but those servers are retired as of 8/2018. Github Pages was the best option available to us, allowing for design flexibility and reliability at no cost. Github Pages only allows *static* websites, which have stability/efficiency/security benefits, but it meant re-doing the lab website. We used to use php to reproduce repetitive portions of code on the old site, e.g. header, footer, navigation etc but that's not an option with a static site. Instead the site now uses Jekyll, which lets you put together the format of each page and use 'variables' where you like to represent those bits of repetitious code. Then when you deploy it, Jekyll compiles everything into html files as if you had typed it all out. (It does this on the Github server; you don't directly upload those compiled files.) There's a little learning curve for novice coders like myself (Chris) but keep playing around with it to try different things and you'll get the hang of it, and probably end up having fun.

The site also relies on Bootstrap v4, which is basically a library you link the site to in order to use a bunch of tools for styling and making the site useable on both large and small screens. We add our own custom styling for the site on top of bootstrap with the file "custom.css".

Assuming you're a novice like me:
1. Get familiar with these (see resources below):
    * html
    * CSS
    * Bootstrap 4
    * how to use Github
    * don't wory about javascript or jquery, just know that they do fancy stuff and you can use the fancy stuff that's already incorporated into bootstrap and by copying the right lines of code from elsewhere if needed
    
2. Setup your computer for coding and previewing your output
    * get sublime text https://www.sublimetext.com
    * get the github desktop client
    * make a branch off of the "master" (you'll work on that branch without affecting the website until you're ready to commit your updates)
    * get Jekyll: http://dquinton.github.io/debian-install/tutorial/22-github-pages.html (section 2)
    * if you like, use something like Automator (on Mac) to automatically open up everything you need to work on the site (sublimetext, github, run Jekyll, open a browser to the local site, etc)

3. Get crackin'. The most frequent updates will be adding new publications, reorganizing the people page, and freshening up the home page with things like new carousel photos.
    * Don't let the site get big. Github says the page shouldn't get bigger than ~1 GB. Lab members will send you unnecessarily HUGE photos; compress/resize them before adding to the site
    * Keep the code organized and use lots of comments. Use names that are descriptive and make sense. Do things the programmer way rather than the brute-force way, e.g. add a class to the CSS file instead of repeatedly typing out in-line style overrides. The old site was a mess. Do better.

Resources:
* w3schools.com (great to learn html, CSS, and Bootstrap)
* https://pages.github.com 
* https://help.github.com/articles/user-organization-and-project-pages/ (the lab website is an "organization page")
* https://learntocodewith.me/tutorials/github-pages/ 
* https://www.labnol.org/internet/free-file-hosting-github/29092/ 
* http://getbootstrap.com/docs/4.1/
* http://getbootstrap.com/docs/4.1/examples/ (good spot to find what you want then copy the code)
* https://hugogiraudel.com/2013/02/21/jekyll/ 
* https://davidwalsh.name/introduction-static-site-generators 



