---
layout: post
title: Remaking this website from scratch [Day Five]
subtitle: Update
categories: Projects
tags: [Making a website]
---
[My website is hosted on github pages, view it here.](https://m-watermelon.github.io/WatermelonBlog-2.0/) 

I was pretty busy yesterday, so I didn't make any changes. However, today I am back to making edits to my website. I was having an issue with the link on the 'About' page that took you back to the home page, I added the `font-family:  Helvetica, Arial, Oswald, sans-serif;` font styling to it, but it still had the gross blocky standard font, so I really wanted to fix it. The issue was really simple: I put a comma (',') instead of a semicolon (';'). I also added the 'skills' list to my about page. 

\[Update]:

I have no idea how, but the 'About' page's footer is at the bottom of the page finally!! I pasted the skills list into the about page html, and I noticed (thanks to the text wrapping of Github) that I still had the `<div id = "button">` still there after I pasted the html I made for my index website (it helps keep everything consistent and saves time), so I deleted it. This, along with the font fix is all I changed before making the commit. I'll try to see why this happened, and hopefully fix the home page too! I'll also check the css files.

Fixes and edits done today:
 - Font fixes with the about page link (takes you back to home)
 - Added skills list
 - Deleted `<div id = "button">` 

\[Update #2]
**I fixed it**!! It was one single `</div>` tag that was ruining everything. On the 'About' page html there were two `</div>` tags before `<footer>`, however in the index html, there was only one, and that second missing `</div>` tag was under `<footer>` instead.
 
 Main priorities:
 - ~Keep the footer at the bottom of the page~ 
 - Adjust the text to be further from the edges of the screen


This is what I have left to add:
- ~Move the footer to the bottom of the page~ \[Complete]
- Archives page
- Tags, Post categories, \[New] post marker
- Post layout
- Consistent site layout that can be applied to pages
- Font sizing
- Make markdown pages for easier use
- And more!
