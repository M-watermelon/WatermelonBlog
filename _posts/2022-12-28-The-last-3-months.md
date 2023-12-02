---
layout: post
title: Distrohopping, Pull Requests, Competitions, & more
subtitle: What I was doing the last 3 months
categories: Posts
tags: [Post]
---


### A quick update
I was pretty busy with school, so I couldn't really write much, but a lot has happened since I last posted. I did all of the things mentioned in the title, as well as learning a ton of new things about linux that are extremely useful all the time. 

### I GOT A THINKPAD
A month after I installed linux on my chromebook because chromeos was annoying me, I got a thinkpad! My chromebook had served me well, but by this time I had used it everday for almost four years, and it was on its last legs. Using a Lenovo Thinkpad T14 Gen 3 has changed my life honestly, because it allows me to do much, much more than my chromebook ever did (thanks to the difference in sheer computing power).

### Discovering Luke Smith's cooking site and learning pull requests!
I often look to youtube for linux tutorials and news, and I eventually stumbled upon Luke Smith's youtube channel. From there, I found his video showcasing his website titled [Based cooking](https://based.cooking/), and I thought hey, maybe I should add a recipe so I can learn to make a commit to a public repository. So I followed the instructions on the readme, and voila, I added a strawberry compote recipe. View it [here](https://based.cooking/strawberry-compote/)

### Computer science Club & Cybersecurity team
I joined the Computer Science club at my high school, and I formed a Competitive Cybersecurity team! Computer science club is once a week, and I host two weekly online meetings for the team on discord, where we talk about linux, competitions, and I demo CTF challenges. I arranged for the team to participate in cyberstart as training, organizing a leaderboard and all, as training for PicoCTF. Then, in March, we'll compete as a team in PicoCTF.

### Ubuntu 22.04 update breaking grub & fixing it || An arduous process of learning from mistakes 

Sometime during the summer, a failed system update to my dual booted ubuntu setup on my pc resulted in 3 months of chaos. I don't remember exactly how this issue began, but I was running ubuntu 20.04 at the time and tried to update the system, and I probably restarted my computer after something froze (big mistake), and when I booted back into ubuntu I was brought to the grub rescue screen each time. 

After hours of research, I went on to try the advanced options for booting into ubuntu, and after trying one recovery mode after another, I eventually got to one that would bring me to a command line and the recovery menu, and after trying options like dpkg, clean, fsck, and grub (admittedly at random), clicking resume to normal boot would work, and it would boot to ubuntu 22.04. However, the strange thing was I couldn't launch a lot of programs, and there was an icon showing the system was unmounted. Nothing would happen if I clicked and tried to mount it. Additionally, trying to laucn firefox would immediately crash ubuntu. I started had also tried a multitude of different grub rescue commands, and trying to find mount points for grub. None of these methods worked, so I backed up any important files, and tried reinstalling ubuntu. However, the issue here was I had no idea how exactly I would accomplish that. So I boot to Windows, open up the partition manager, and delete all the partitions on the ubuntu ssd (I had two separate ssds) which makes the problem even worse. But back then, I had no idea (woops), and just reinstalled ubuntu (again). This time, I ran the boot repair tool following [this tutorial](https://www.howtogeek.com/114884/how-to-repair-grub2-when-ubuntu-wont-boot/). Then, after everything, I pulled the plug and decided to install popOS, and voila. Miraculously popOS fixed the whole issue, and its been the same ever since. **So when all goes wrong, install popOS.**

And that, is a beginner's first sysadmin trainwreck. 

### My experience with distro hopping
I was a pretty conservative ubuntu user up until the chaos with the new update ensued. I was researching other linux distrubutions but I didn't really have any motive to switch. As I mentioned earlier, I switched to Pop OS by System 76 on my main computer. Because it's based on ubuntu, it was pretty easy to switch. 
Then, this fall I installed Kali linux on my chromebook after jailbreaking it, [which is covered in this post.](https://m-watermelon.github.io/WatermelonBlog/linux/2022/12/28/Linux-On-Chromebook.html) After that, I started realizing that kali linux isn't really that good of a daily driver, despite its uses for cybersecurity CTFs. So, I started researching good linux distros that are relatively lightweight. And from there, I found it. My current daily driver and favorite linux distro: Arch Linux. Yes, I use arch btw. Configuring and making arch usable was a relatively large learning curve for me, but it was definitely worth it. Thanks to installing arch linux, I managed to significantly improve my linux and command line skills, and bash scripting even. 

### Exploring Desktop environments and DWM Configs on arch!
After installing arch linux, I started watching more of Mental Outlaw's youtube videos, specifically all the arch linux tutorials he has. This lead me to stumble upon his dwm videos, which got me interested in using other desktop environments, besides the beloved xfce. XFCE4 is great and all, but I wanted to try something new, specifically a tiling window manager. It was yet another steep learning curve, but thanks to Mental Outlaw's and Bugswriter's videos, I learned to configure DWM to how I like it, and this was my introduction into linux ricing.

### Participating in Advent of Code
I was introduced to Advent of Code this winter, and I solved up to day 8. My solutions are probably a bit janky, but I got a lot of good practice out of this competition. Solutions are in this repo: https://github.com/M-watermelon/Competition-programs.
