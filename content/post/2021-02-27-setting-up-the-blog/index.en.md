---
title: Setting Up The Blog
author: R package build
date: '2021-02-27'
slug: new-test-for-post
categories:
 - Test
tags:
  - Blog
  - Hugo Themes
  - Setting Up The Blog
description: Quick tour on how i've struggled through the creation of this blog
image: pawel-czerwinski-8uZPynIu-rQ-unsplash.jpg 
math: ~
license: ~
hidden: no
comments: yes

---
All right, let's cut to the chase, creating this Blog with RStudio, blogdown, and Hugo themes after just a week of introduction to R programming for my MSc's program, was hella hard and a pain in the butt. I'm not gonna lie. 

Most of the tutorials/how-to that you can find online, be it on video format or another person's blog, are absolutely great; for them and for their settings and probably won't transfer as well as you might think in your specific case. There's always some troubleshooting you gotta do that's not covered anywhere and you might need to come up with something on your own, merging together tips from others. I'm not saying it's impossible of course, but I was surprised to see how hard and sometimes no sense (at least for now, I'll probably get better in the future) it is.

Even with blogdown and Hugo, which should be the no-brainer-JavaScript-HTML-free way of making a blog, was hard af. I'd chosen a different theme to start with but had to drop it after not being able to troubleshoot a deploying problem. 

Enough with the rant, let's spread some positive vibes, shall we?

# Relevant Resources
1. [Main Article from Bobby Muljono (towards data science)](https://towardsdatascience.com/a-data-analysts-guide-to-creating-your-personal-website-with-r-f0079ba9b81c)  
2. [Setting up GitHub repo](https://medium.com/@aklson_DS/how-to-properly-setup-your-github-repository-mac-version-3a8047b899e5)  
3. [Hugo Stack Theme](https://themes.gohugo.io/hugo-theme-stack/)
  
  
    
All the relevant references are here, but you are most likely to do some good ol' googling, to find out everything you need.

TL;DR you create a new repo on RStudio with blogdown where you choose your theme, create a repo on GitHub that will be integrated with Git, modify your theme (this is the hardest part btw, but you'll get better once you get used to it) and finally, you need a platform that deploys your website and hosts it (in my case I've used Netlify, that takes your files in your GitHub repo and turns it into what you are seeing now).

Though the process is quite straightforward, once you get to the personalization of your website, that's when it gets tricky. There should be, and that's not always the case, so keep that in mind, documentation for every Hugo theme you decide to use and general documentation on the architecture of Hugo and the syntax. Basically, documents that explain how Hugo thinks. And, that's as crucial as it gets. Once you've entered that rabbit hole, all you gotta do is figure out through trial and error what goes where, and when the blog throws a tantrum because that goddamn image is not in the right folder. If you are like me and have absolutely zero coding/computer science background, sometimes the terminology used makes no sense whatsoever and the only way out is to bang your head against a wall multiple times before getting to that "oh god, thanks it worked" moment. Last tip i can give you is to look at the examples provided , build the server on local host and tweak them as much as you can. That will hint you what you can and cannot do in order to manipulate the layout of the blog.


That's it, this was mostly a general test for me, about the blog and the text piece, which was a lot harder than I thought it would. Juicier things are coming about coursers imma about to take and report here, and a general overview of the Msc program I'm currently in.

See ya!
