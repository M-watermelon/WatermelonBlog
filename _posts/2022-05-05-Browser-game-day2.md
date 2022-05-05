---
layout: post
title: Making a browser game [Day two]
subtitle: Update [Day ~8 of making a website from scratch]
categories: Projects
tags: [Making a website]
---
### Updates
I decided to switch from Javascript to Python, because I'm a little more experienced with it, and I always wanted to try using pygame and tkinter to make a game. I'm still making a snake game though.

### Key takeaways

I was having issues with `import tkinter as *`, I was recieving an error that said the program couldn't find a module named 'tkinter',  but after doing some more research, I found out that I didn't have tkinter properly installed. The method of installing that worked for me was `sudo apt-get install python3-tk`. After that, I managed to get a little pop up to open that also had the quit button. I'm currently using the ttk (Themed tkinter) widget of tkinter, and learning to use it at the same time.

I'm working on the opening screen currently, I probably should just start with making an outline of the game, but I want to experiment and try out the features of tkinter and tkk first.
 



### My plan:

1. Set up the basic html formatting and css styles   \[DONE\]
2. Make the basic canvas and shapes using python
3. Add animations and movement using keys
4. Add border/collisions to canvas
5. Polish and add extra features like items/fruits, scores, health 
