---
author: 
categories:
- Theme Features
date: "2021-07-13"
draft: false
excerpt: Finally a website!
layout: single
subtitle: My journey with blogdown
tags:
- website
title: My journey with blogdown
---

I finally have a website! Initially, I wanted to learn html, css, javascript, and build it myself. But, I decided that would be a poor use of my time. As I became more proficient in R, I learned about packages that could streamline the process. This website is built in R studio using the [blogdown package](https://bookdown.org/yihui/blogdown/). Each page is written in markdown or Rmarkdown. Blogdown uses the Hugo framework to generate static sites. The great things about static sites are that they are portable, independant, fast, and secure. Hugo websites are built with [themes](https://themes.gohugo.io/), user-submitted templates. At first I used the [academic theme](https://wowchemy.com/) from wowchemy by George Cushen. I found it to have the best documentation and feature list. But I wanted to further customize the theme so I had to teach myself a good bit of css and html. There are tons of great resources out there for this but using google chrome’s inspect action was key. Then my website was beautiful, it was done. I went to deploy it using netlify and...error. I figured I had messed something up so I decided to start from scratch and just transfer the files I had written to a new site. As I was doing that I realized that the wowchemy theme had transitioned to become more of an online cms editor. Now it no longered worked with the blogdown package. So I decided to use a different theme called hugo-apero.I am sure I will have more to say about this theme as I use it more. Oh, one final thing. Don’t put your website repository in a google drive folder. It won’t work.
