---
layout: post
title: Distrohopping, Pull Requests, Competitions, & more
subtitle: What I was doing the last 3 months
categories: Posts
tags: [Post]
---

#### (Still a work in progress!)



### A quick update
I was pretty busy with school, so I couldn't really write much, but a lot has happened since I last posted. I did all of the things mentioned in the title, as well as learning a ton of new things about linux that are extremely useful all the time. 

### Discovering Luke Smith's cooking site and learning pull requests!
I often look to youtube for linux tutorials and news. 

### Computer science Club & Cybersecurity team
I joined the Computer Science club at my high school, and I formed a Competitive Cybersecurity team! Computer science club is once a week, and I host two weekly online meetings for the team on discord, where we talk about linux, competitions, and I demo CTF challenges. I arranged for the team to participate in cyberstart as training, organizing a leaderboard and all, as training for PicoCTF. Then, in March, we'll compete as a team in PicoCTF.

### Ubuntu 22.04 update breaking grub & fixing it || An arduous process of learning from mistakes 

Sometime during the summer, a failed system update to my dual booted ubuntu setup on my pc resulted in 3 months of chaos. I don't remember exactly how this issue began, but I was running ubuntu 20.04 at the time and tried to update the system, and I probably restarted my computer after something froze (big mistake), and when I booted back into ubuntu I was brought to the grub rescue screen each time. 

After hours of research, I went on to try the advanced options for booting into ubuntu, and after trying one recovery mode after another, I eventually got to one that would bring me to a command line and the recovery menu, and after trying options like dpkg, clean, fsck, and grub (admittedly at random), clicking resume to normal boot would work, and it would boot to ubuntu 22.04. However, the strange thing was I couldn't launch a lot of programs, and there was an icon showing the system was unmounted. Nothing would happen if I clicked and tried to mount it. Additionally, trying to laucn firefox would immediately crash ubuntu. I started had also tried a multitude of different grub rescue commands, and trying to find mount points for grub. None of these methods worked, so I backed up any important files, and tried reinstalling ubuntu. However, the issue here was I had no idea how exactly I would accomplish that. So I boot to Windows, open up the partition manager, and delete all the partitions on the ubuntu ssd (I had two separate ssds)

### My experience with distro hopping
I was a pretty conservative ubuntu user up until the chaos with the new update ensued. I was researching other linux distrubutions but I didn't really have any motive to switch. As I mentioned earlier, I switched to Pop OS by System 76 on my main computer. Because it's based on ubuntu, it was pretty easy to switch. 


### Exploring Desktop environments and DWM Configs on arch!


