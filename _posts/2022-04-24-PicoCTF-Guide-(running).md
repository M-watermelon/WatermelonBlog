---
layout: post
title: Useful things to know for Pico CTF, Cyberstart, and general cybersecurity
subtitle: A running guide
categories: Guide
tags: [Guide]
---
First published on April 2, 2022.

### This guide is going to be a running blog post, meaning I'll constantly be updating this page with new things I learn.

Just to start, here's a basic list, organized by topic of cybersecurity stuff I know about/have heard of. This list includes tools, concepts, attacks, commands, etc. It's going to get pretty long, so I'll have individual posts that I'll link here about each topic.
- Web exploitation:
  - Inspecting a website's source code
    - Using the console
    - console.log(email,password)
  - SQL injection
  - Man in the middle attack

- Forensics:
  - Steganography -> the method of hiding information inside files (often inside images).
    - Pixel inversion
    - Audio steganography
    - Video steganography
    - Image overlapping
    - Stegsolve

  - Binwalk
  - [evtxexport](http://manpages.ubuntu.com/manpages/focal/man1/evtxexport.1.html)
  - Hexdump
  - Sleuthkit
  - Exiftool
  - Sonic Visualizer
  - Mimetype
  - Strings
  - unar
  - ar
  - 7zip

- Binary exploitation:
  - Endian: Big Endian and Little Endian

- General terminal commands:
  - ls -> lists the files and folders inside a directory
  - ls -a -> view hidden files
  - ls -l -> "Lists all files and folders, each on a separate line, and provides additional information about them (permissions, ownership and modified date). " [Source](https://www.siteground.com/tutorials/ssh/listing/)
  - ls –alR -> lists all files (even hidden ones), adds descriptions, and will also list subfolders, their contents, and their descriptions
  - cd -> return to the first directory (root)
  - cd DIRECTORY -> enter a directory/folder
  - chmod +x filename -> make a file executable
  - ./filename -> run the file
  - whoami -> get the user id in the terminal
  - python3 filename -> run a python 3 program
  - cat -> output contents of a file
  - nano filename -> edit a file inside the terminal
  - /etc/passwd   and /etc/shadow -> these files contain passwords
  - ssh username@ip.add.r.ess -p[PORT]  -> remote login
  - grep -Ril "pattern" directory -> search an entire directory for a string *(depending on the situation, you might need to use "" or / for the directory)*
  - printf 'yourtext' | ./yourprogram     -> run a program and automatically enter an input
- Reverse engineering:
  - GDB -> GNU Project Debugger

- Cryptography:
  - RSA algorithm
  - Diffie-Hellman key exchange
  - Pollard-Rho algorithm
  - Weak RSA primes, weak N value
  - Salts and Hashes
    - MD5, SHA-256, MD4, etc
  - Alice (message sender), Bob (message reciever), and Eve (the eavesdropper) -> common names used when explaining RSA
  - Symmetric and asymmetric key encryption
  - Public and private keys
  - Timing attack
  - Frequency attack
  - Railfence cipher
  - Columnar transposition cipher
  - Transposition/Permutation cipher: eg (1,2,3) -> (2,1,3)
  - Caesar cipher
  - Substitution cipher & frequency analysis
  - Vignere cipher
  - Arnold cipher
  - Atbash cipher
