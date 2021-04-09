---
layout    : single
title     : "How to use GitHub Pages, Jekyll and KaTeX together"
header    : 
  overlay_image       : /assets/images/dr-jekyll-and-mr-hyde-cbdda7-1600.jpg
  overlay_filter      : 0.5
  show_overlay_excerpt: false
  image_description   : >-
    Old-timey illustration showing a scene from Dr Jekyll and Mr Hyde
  caption             : >-
    Image Credit: Theatrical poster collection (Library of Congress)
toc       : true
toc_label : "Contents"
toc_sticky: true
toc_icon  : "list"
date      : 2021-04-09 15:52:11 +0100
katex     : true
categories: jekyll blog howto katex
---

If you ever wanted to create your own website for a blog, _GitHub Pages_ is a
very good option.  You can just create a new repository, go to settings, head
to the GitHub Pages section, choose a theme and you're good to go --- just
start typing posts in markdown.  GitHub will build the website using a program
called *Jekyll* and do the hosting for free (as long as you don't want a custom
URL).  

There are some limits to customisation in this approach though.  In my case
(since I knew I would write about physics and math) I wanted to use
[$$\KaTeX$$](https://katex.org/) which is a library for displaying
LaTeX-generated math formulas on the web. This requires installing a host of
plugins such that Jekyll can build a website with KaTeX support.  The problem:
GitHub Pages only allows websites to use a handful of whitelisted plugins for
security reasons. That meant I couldn't use GitHub Pages to build the website.
But there is another option: You can build the website yourself using Jekyll on
your own computer than upload the generated files to GitHub which produces a
fully functioning website regardless of what plugins you have used.

### Setting up Jekyll


### (Optional) Setting up Minimal Mistakes theme


### Adding KaTeX functionality to the website


### Hosting the site on GitHub
