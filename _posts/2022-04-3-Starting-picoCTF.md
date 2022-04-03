---
layout: post
title: Getting started in cybersecurity with PicoCTF
subtitle: A guide for beginners
categories: Guides
tags: [Guides]
---
### Introduction
[PicoCTF](https://picoctf.org/) is a fun cybersecurity competition for students from middle school to high school. CTF stands for 'Capture The Flag', this is referring to the main objective of PicoCTF. In PicoCTF, you are given challenges, puzzles related to important cybersecurity topics and your goal is to find the 'flag' which is a special code (usually in the format of picoCTF{flag}). You enter this flag into the challenge to gain points. 

I first started competing last year in a team with my friends, the issue was though, that we had no idea about anything related to cybersecurity. I couldn't find a guide that either didn't overwhelm me or confuse me, so, I'm going to attempt to make a simple- yet thorough guide that will hopefully make getting into cybersecurity easier.  
### Programming and Cybersecurity
Programming and cybersecurity are very intertwined things, you need programming for cybersecurity, cybersecurity for programming. I highly suggest learning basic programming and terminal usage before, or while you learn cybersecurity.
### So: Where do you begin?
I reccomend first familiarizing with the different types of categories (think of them like genres) in cybersecurity. PicoCTF did a good job of organizing them (I will be using this throughout my blog too):
- General topics
  - Basic skills
- Web exploitation -> Involving websites
  - Finding weaknesses in websites, and attacking it, *exploiting* that weakness
- Binary exploitation -> Involving programs
  - Finding a program's weakness, attacking it, using a program for unintended uses, or getting the information that you want from a program
- Forensics - Involving files
  - Given a file or folder, you need to find out what is special about it, find certain peices of information or another file
- Cryptography -> Involving methods of hiding information
  - Decoding and breaking secret codes, finding out what makes the secret code breakable
- Reverse engineering -> Involving the unscrambling of code
  - Given a program, you need to understand its function, what makes it special, and decode it if someone tried to make it unreadable

I simplified these topics a lot, just so that its easier to get a general understanding of them. As you get to learn more about these topics, you will see that there is a lot more to them than these simple definitions.
### What you will need:
- A computer/laptop
  - You should preferrably use Windows, Linux, or Mac os (a Raspberry pi that runs debian or ubuntu depending on the generation, would be great too)
  - It is possible to work with chromebooks too, I will make a tutorial for that soon

### Research
You are going to have to learn a lot of new things and learn to use a lot of new applications, so I suggest that you do lots of research, find the tools that best fit you, be it VSCode for programming, or Atom for example.
I've gathered a couple of handy resources that I still use today as a reference for cybersecurity. 
Here is a list of them:
- [Pico primer](https://primer.picoctf.com/): This website might have some parts that are a little out of date, but it is a very comprehensive guide for beginner to intermediate levels.
- [PicoCTF's website](https://picoctf.org/resources): PicoCTF's own website has a wealth of information and links to useful websites, along with pdfs that have basic introductions to the categories of cybersecurity.
- [Khan academy cybersecurity 101](https://www.khanacademy.org/partner-content/nova/nova-labs-topic/cyber/v/cybersecurity-101): I suggest starting here if you are an absolute beginner.
- [CTF Field guide](https://trailofbits.github.io/ctf/): This is a good reference and intermediate guide to cybersecurity.
- [Cheatsheet - Steganography 101](https://pequalsnp-team.github.io/cheatsheet/steganography-101): This is one of my favorite cheatsheets for forensics, it focuses on steganography, which is a method of hiding information inside files, visually, or in audio files.
- [Sleuthkit and autopsy](http://www.sleuthkit.org/): Sleuthkit and autopsy are tools that are very useful for forensics. I highly reccomend checking them out.
- [Hack tricks](https://book.hacktricks.xyz/): This is less of a resource for PicoCTF as it is a resource for cybersecurity.
- [PicoCTF Preparations](https://adamdoupe.com/blog/2013/04/10/picoctf-preparations/): Another great place to start for PicoCTF. This is probably one of the most **beginner friendly** guides I have seen.
- [ASCII, Hex, Binary, Decimal, Base64 converter](https://www.rapidtables.com/convert/number/ascii-hex-bin-dec-converter.html): This is a tool, its to convert numbers and letters from different methods of expressing them, like decimal numbers to binary.
- [RSA algorithm calculator and guide](https://www.cs.drexel.edu/~jpopyack/IntroCS/HW/RSAWorksheet.html): This is essentially a walkthrough of the RSA algorithm (cryptography), it helped me understand RSA, and even solve a couple PicoCTF challenges. Its a great intro to RSA if you are daunted by all of the equations.
- [Youtube: Art of the problem](https://www.youtube.com/user/ArtOfTheProblem): This is one of my favorite youtube channels, it is pretty beginner friendly and the videos are wellmade. I highly suggest checking out their video for RSA encryption! 
- [Youtube: Computerphile](https://www.youtube.com/user/computerphile): This is a more advanced channel that explains more technical aspects of cybersecurity and programming. This is the number one channel I would reccomend for a deeper dive into cybersecurity.
- [Youtube: Fireship](https://www.youtube.com/channel/UCsBjURrPoezykLs9EqgamOA): The Fireship channel is a little closer to entertainment and further from cybersecurity, but it is great for familiarizing yourself in the cybersecurity and programming world.
- I will add more resources as I find them in the future!

### One of the best ways to learn is through practice, PicoCTF not only hosts competitions, but you can practice on [their website](https://play.picoctf.org/practice).

### Conclusion
Cybersecurity and programming aren't easy. There is a learning curve that depends on you. It might be steep and you might be bombarded by tons of technical terms or you might breeze through it, everyone's different. Sometimes you  might get stumped on PicoCTF challenges or some problem in your program and it could get frustrating, but nothing is more satisfying than that final eureka moment. Also, cybersecurity and programming, computer science in general, is going to be a lot of math. Depending on the person, that might be a good thing or a bad thing. Cryptography, the security of our internet is heavily based on math, from the simple Caesar cipher, shifting letters by a couple places, to frequency attacks, the measure of how often a letter occurs in a text in comparison to English (if 'q' occurs the most often in the code, it could be 'e', the most common letter in English), to Salts and Hashes, randomizing and chopping up information in a way that can't be reversed, to RSA, an algorithm based on two prime numbers and their product. One thing to keep in mind is that computer science jobs can pay pretty well, even at the starting level!
