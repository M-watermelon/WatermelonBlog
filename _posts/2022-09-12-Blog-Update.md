---
layout: post
title: Recent and Upcoming Blog Site Changes
subtitle: Making this site better
categories: Development
tags: [Development update]
---
#### Originally publieshed 8/14/22, with many updates since then.

---


## What I've already done:



I changed the dark theme colors to a warmer tint. 

If you look at the [source code to this website](https://github.com/M-watermelon/WatermelonBlog) on github, you'll notice I made a couple commits with pretty similar edit messages - "changing dark mode colors" , "color changes again". That's because I forgot which file determines the final outcome of the website appearance-wise. I was testing changes to CSS files to find out which one will make the permanent color-theme change. There definitely were smarter alternatives I considered, but I was tired. 

For future note: use `_sass/yat/_dark.scss` and `_sass/yat/_layout.scss` to implement theme changes. `_sass/yat/_base.scss` can be used to change the colors of things like links and also add more elaborate styling.

---

I attempted to change the url of the homepage of the website, to be shorter.

Note, it hasn't worked yet, and I'll continue trying to fix it. I'll add the fix to that here later, but so far I've tried changing it in the github pages settings and changing it in `_config.yml`. Neither worked, so I'll probably just google it or look into republishing the website. 

EDIT: I finally understand why I cannot remove the `/WatermelonBlog/` in the url. This is due to the fact that I have not configured a custom domain for my website (and I probabkly won't in the future.) The reason it is `https://m-watermelon.github.io/WatermelonBlog/`<mark>`WatermelonBlog/`</mark> and not `https://m-watermelon.github.io/WatermelonBlog/`<mark>`home`</mark> is because 'WatermelonBlog' is the name of the github repository from which I created a github pages environment.

This is a goofy mistake, but better to find out late than never. I found this out only after launching a *second* github pages website, that had the url `https://m-watermelon.github.io/`<mark>`Uranium-cat/`</mark>. I had considered the (rather obvious) possibility that the urls are made from my github account username, .io, and the repository name, but I never decided to look into it. 

The more you know!! 

---

Update: That's pretty much all. I'll keep working on this from time to time, but my main focus is school (which has started again) and BASH scripting.

## Two more things:

1) I really want to add comments to this website, or at least a method of communicating with people who read these (if anyone reads them). Chances are the hypothetical commenters would be my friends, with whom I share the progress of my projects. But I'm a bit too worried about troll comments to implement a comment system. What I would want to do is the second option I mentioned; creating some convenient way within the website for a reader to contact/say something to me.

2) This blog is the result of my dream to have a neat/cute Tumblr style website/blog. When I originally thought of it, I intended for it to be mainly for art. This is why I want to create a sub section of this website devoted to art in the future.

---