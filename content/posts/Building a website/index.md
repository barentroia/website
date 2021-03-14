---
title: "Building a website using Hugo/Netlify"
date: 2021-03-14T08:06:25+06:00
description: My experience with building my website using Hugo/Netlify
menu:
  sidebar:
    name: Tech posts
    identifier: tech
    weight: 10
---

If you liked my website and would like to build a similar one, I can tell you that it’s not that difficult, as long as you already have some experience with programming and with Git.

Overall, these are the steps you'll have to follow:
1. Decide which platform you want to use. This [blog post](https://www.techighness.com/post/why-i-chose-hugo-framework-for-my-first-blog/) makes an extensive comparison of platforms you can use. I ended up choosing Hugo for several reasons:
	- Price: Hugo is free and a small site like mine can be easily hosted for free in netlify. 
	- Security & Speed: Static sites are quite safe and fast.
	- Nice Template: I really liked the Toha template (which is the one I'm using) so I figured I wouldn't have to spend too much time tweaking the template.
	 
	\
	However, if you're not familiar with programming, Git or markdown, building a website with Hugo will likely take more time compared to using a platform like Wix/Wordpress.  

2) If you also decided Hugo is also a good choice for you, create a Git repository for the website. Note that the name of this repository should be \<your username\>.github.io if you want to deploy the website on github pages.

3) Choose a Hugo template at [https://themes.gohugo.io/](https://themes.gohugo.io/).

4) Try to find a starting guide for your template. I would recommend that you build the main structure first, without customizing it, and check that the website can still be generated after each modification you do. When I first built my website I made a lot of small mistakes but it was easy to catch them because I checked each modification at the time. If there is little information on your template, I found the documentation on the [Toha template](https://toha-guides.netlify.app/posts/) quite useful. There should be some similarities in the structure of the files/syntax. 

5) Deploy your site in Netlify (or gituhub pages).

My experience with this template has been quite good, both because I haven't felt the need to modify the template that much and because the documentation is quite clear. 

Compared to other platforms like Wix/Wordpress, it can take more time to understand how to customize the template. However, it gets easier once you understand the basics!

Hope this post has been helpful. I will keep updating the post as I modify the website more. Please let me know if some links are now working anymore :) 