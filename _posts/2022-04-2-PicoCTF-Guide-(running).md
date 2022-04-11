---
layout: post
title: Useful things to know for Pico CTF and general cybersecurity
subtitle: A running guide
categories: Guide
tags: [Guide]
---

### This guide is going to be a running blog post, meaning I'll constantly be updating this page with new things I learn.

Just to start, here's a basic list, organized by topic of cybersecurity stuff I know about/have heard of. This list includes tools, concepts, attacks, commands, etc. It's going to get pretty long, so I'll have individual posts that I'll link here about each topic.
- Web exploitation:
  - Inspecting a website's source code
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
  - cd -> return to the first directory (root)
  - cd DIRECTORY -> enter a directory/folder
  - chmod +x filename
  - ./filename
  - whoami -> get the user id in the terminal
  - python3 filename -> run a python 3 program
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
