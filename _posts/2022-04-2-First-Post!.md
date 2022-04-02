---
layout: post
title: My first post!
subtitle: Hello world
categories: Posts
tags: [Post]
---
This has been a really annoying journey to making a website. 
I encountered three main issues:
- Missing theme file
- Didn't enter a url and url subpath in \_config.yml
- Put a wrote /assets/images/banners/imagefile.png instead of assets/images/banners/imagefile.png

All of these were really simple mistakes, I'm not exactly sure which file specifically I was missing for the theme I used but I managed to fix it by trying again and pushing all of the theme files to the github repository.

Key takeaways:
- Make sure the urls you add to \_config.yml are the same as the github page one.
- **Don't** put a / before the first folder name.

I also struggled with adding a favicon, I'm not sure what went wrong, but I guess it just took some time along with a few commits for it to work? It likely works because in head.html, I added this line `<link rel="shortcut icon" type="image/png" href="/assets/images/banners/favicon.png">` its under `<link rel="stylesheet" href="{{ "/assets/css/main.css" | relative_url }}">`.
