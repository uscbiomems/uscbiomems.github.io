# biomems.usc.edu - Website of the Biomedical Microsystems Laboratory at USC

The website files are stored and managed in the repository https://github.com/uscbiomems/uscbiomems.github.io. To get editing privileges, contact larsonce@usc.edu.

GitHub Pages website launched 20180725 by larsonce@usc.edu

## Development/maintenance notes for future website superusers of the lab:

The previous version of the lab website was hosted on USC's servers, but those servers are retired as of 8/2018. GitHub Pages was the best option available to us, allowing for design flexibility and reliability at no cost. GitHub Pages only allows *static* websites, which have stability/efficiency/security benefits, but it meant re-doing the lab website. We used to use PHP to reproduce repetitive portions of code on the old site, e.g. header, footer, navigation etc but that's not an option with a static site. Instead the site now uses Jekyll, which lets you put together the format of each page and use 'variables' where you like to represent those bits of repetitious code. Then when you deploy it, Jekyll compiles everything into html files as if you had typed it all out. (It does this on the Github server; you don't directly upload those compiled files.) There's a little learning curve for novice coders like myself (Chris) but keep playing around with it and try different things. You'll get the hang of it, and probably end up having fun.

The site also relies on Bootstrap v4, which is basically a library you link the site to in order to use a bunch of tools for styling and making the site useable on both large and small screens. We add our own custom styling for the site on top of bootstrap with the file "custom.css".

Assuming you're a novice like me:
1. Get familiar with these (see resources below):
    * html
    * CSS
    * Bootstrap 4
    * how to use Github
    * don't wory about javascript or jquery, just know that they do fancy stuff like making objects disappear and move, and that you can already use the fancy stuff that's incorporated into bootstrap (and if needed, by copying the right lines of code from elsewhere)
    
2. Setup your computer for coding and previewing your output
    * get sublime text https://www.sublimetext.com or some other text editor
    * get the github desktop client (if you haven't already, make a GitHub account and have the lab website superuser invite you to github.com/uscbiomems)
    * make a branch off of the "master" (you'll work on that branch without affecting the website until you're ready to commit your updates)
    * get Jekyll: http://dquinton.github.io/debian-install/tutorial/22-github-pages.html (section 2)
    * if you like, use something like Automator (on Mac) to automatically open up everything you need to work on the site (sublimetext, github, run Jekyll, open a browser to the local site, etc)

3. Get crackin'. The most frequent updates will be adding new publications, reorganizing the people page, and freshening up the home page with things like new carousel photos.
    * Don't let the site get big. Github says the page shouldn't be bigger than ~1 GB. Lab members will send you unnecessarily HUGE photos; be sure to compress/resize them before adding to the site. If more space is needed in the future, consider moving the publication pdfs to something like a free Google Drive account.
    * Keep the code organized and use lots of comments. Use names that are descriptive and make sense. Do things the programmer way rather than the brute-force way, e.g. add a class to the CSS file instead of repeatedly typing out in-line style overrides. The old site grew to become a mess and that made it difficult to manage. Do better.

Resources:
    * https://www.w3schools.com (great to learn html, CSS, and Bootstrap)
    * https://guides.github.com/activities/hello-world/
    * https://guides.github.com/introduction/flow/
    * https://pages.github.com 
    * https://help.github.com/articles/user-organization-and-project-pages/ (the lab website is an "organization page")
    * https://learntocodewith.me/tutorials/github-pages/ 
    * https://www.labnol.org/internet/free-file-hosting-github/29092/ 
    * http://getbootstrap.com/docs/4.1/
    * http://getbootstrap.com/docs/4.1/examples/ (good spot to find what you want then copy the code)
    * https://hugogiraudel.com/2013/02/21/jekyll/ 
    * https://davidwalsh.name/introduction-static-site-generators 
    * https://jekyllrb.com/docs/home/




