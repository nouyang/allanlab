# Quickstart

To control so not at yournam.github.io
```
rm cNAME
? git checkout gh-pages
git merge master
 ? git checkout master
 git branch -d gh-pages
 gcm "remove branch?"
 2048  git push origin --delete gh-pages

vi _config.yml
baseurl: "/"
url: "" 
```

Not sure which of the above was necessary, but those are some things I
tried...

Go to https://github.com/nouyang/allanlab/settings
Make sure it says "your site is published at `*.github.io/allanlab`
(if it says "ready to be published", wait a minute for server to update))

So, now I have another repository (my_portfolio) pointed at myname.com, and
this one shows up at yname.com/allanlab and the javascript loads correctly

# Allan Lab Website

This is the website of our academic research group at Leiden University.

This website is powered by Jekyll and some Bootstrap, Bootwatch. We tried to make it simple yet adaptable, so that it is easy for you to use it as a template. Plese feel free to copy and modify for your own purposes.  You don't have to link to us or mention us (but of course we appreciate it).

Go to *aboutwebsite.md*  to learn how to copy and modidy this page for your purpose. 


Copyright Allan Lab. Code released under the MIT License.

