---
layout: single
title:  "How I created this blog using Jekyll, GitHub Pages and KaTeX"
header: 
  overlay_image: /assets/images/dr-jekyll-and-mr-hyde-cbdda7-1600.jpg
  overlay_filter: 0.5
  show_overlay_excerpt: false
  image_description: "Old-timey illustration of Dr Jekyll and Mr Hyde"
  caption: "Image Credit: Theatrical poster collection (Library of Congress)"
date:   2021-02-11 15:52:11 +0100
katex: True
categories: jekyll blog howto katex
---

In my first blog post I will show you how I built the website for this blog.
Since I wanted to write about physics, I needed some way to incorporate 
$$\LaTeX$$ typesetting into the website. For this I used a library called
[$$\KaTeX$$](https://katex.org/) that easily enables LaTeX usage on the web.
To host the blog I decided to use GitHub Pages which itself relies on 
[Jekyll](https://jekyllrb.com/), a 
[Ruby](https://en.wikipedia.org/wiki/Ruby_(programming_language))-based static 
site generator.

### Running into trouble
Well, the task sounded easy enough at first, but there was a complication.
After setting up and playing around with my first GitHub Pages website I
discovered a crucial limitation. GitHub Pages builds its websites with a
sanitized version of Jekyll's `build` command. 
