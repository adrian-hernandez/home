---
layout: post
title: "Emulation of PS1 Games in 2024"
date: 2024-11-26
excerpt_separator: <!--more-->
---

While studying algorithms, I decided to listen to music from some of my favorite PS1 games. It was nostalgic and fun to hear them again. I decided to attempt to get them running in 2024.

<!--more-->

## Background
A few years ago I was able to setup ePSXe, a PS1 emulator, on my Windows laptop. While it was a great emulator, it required a lot of manual setup. I wanted to see if I could get some PS1 games running in 2024 without all the hassle.

## RetroArch: A Modern Solution

RetroArch is a powerful and flexible emulator frontend that supports a wide range of systems. It has a modular design that allows for easy addition of new cores and plugins.

I was pleasantly surprised that RetroArch had a PS1 core called SwanStation (formerly knows as DuckStation). I had never used it before but it worked beautifully. Its UI is clean, modern, and intuitive, and its performance was sufficient for most PS1 games.

![RetroArch User Interface]({{ '/assets/images/posts/2024-11-26-emulation-of-ps1-games-in-2024/retroarch-main.png' | relative_url }})

![SwanStation Settings]({{ '/assets/images/posts/2024-11-26-emulation-of-ps1-games-in-2024/retroarch-settings.png' | relative_url }})

## BIOS Setup
Similar to other emulators, RetroArch requires BIOS files for the PS1. Thankfully, there are many resources online to learn how to obtain them. I do own a PS1 so all of this was legal.

## Controller Support
DualShock controllers are automatically detected by RetroArch, wirelessly via bluetooth or wired, and mapped to the correct buttons. If there is need for further configuration, that can be done at the core level or game level which allows for great flexibility.

## Quality of Life Features
Like other emulators, RetroArch supports save states. While some games were entertaining because of how challenging they were, most of the time the difficulty arose from the fact that game saving opportunities were limited. This led to excessive trial and error. Save states made retrying sections much easier.

Fast forwards is another great feature that enhances the gaming experience tremendously. It allowed me to skip cutscenes and other parts that I was already familiar with, making replaying sections more enjoyable.

## Conclusion
Overall, I was impressed with how well RetroArch and SwanStation worked. I was able to get all my games running in a relatively short amount of time and my small break from studying was a great trip down a very nostalgic memory lane.
