---
title: "FinderFix"
date: 2018-11-19T10:47:58+10:00
draft: false
image: "images/apps/finderfix.png"
intro_image: "images/screencasts/01-ff-video.mp4"
intro_image_preview: "images/screencasts/01-ff-preview.png"
intro_image_absolute: true
intro_image_hide_on_mobile: true
extra_image: "images/screencasts/02-ff-video.mp4"
jobtitle: "Utilities"
linkedinurl: "https://www.linkedin.com/"
promoted: true
weight: 1
layout: app
---

**Give extra powers to your Finder windows!**

If after all those years of using your Mac you are still fighting with Finder to get it to behave as you wish, look no further, **FinderFix** will get it to open every new window in the exact same position and size you want it to.

<!--break-->

If you look for an answer to _"How do I get Finder to remember its size and position?"_ on the web, you find literally dozens of non-working answers.

Here's the typical reaction:

> Why doesn't Finder remember the damn window size and location? I keep reading crap about holding down Option key while dragging but that doesn't work. It just reverts back to its microscopic size the next time I open it. It's useless and very tedious and it really aggravates me.

> How do I make this thing stay the way I want it to? I don't mind playing around with system stuff or running scripts - so long as I only have to do it once only.

The only working solution until now was FinderMinder. It was rudimentary, had its own warts, like having to hide it on each computer restart, but as far as resizing and setting Finder's position was involved it just worked. However, what worried me about it was that there had been no new releases since 2016. It was showing its age with a 32-bit PowerPC universal binary and its use of quite a lot of private APIs. What's more, it relies on some very slow AppleScript calls to solve the task at hand.

Additionally with M1 Apple silicon chips "on my door steps", I felt the urge to write an alternative in pure modern and fast Swift in an M1 Universal Binary 2.

Then with the announced demise of TotalFinder, I started porting some of its features to **FinderFix**. It's not yet a full replacement of TotalFinder but it already has some of its essential features without compromising the **System Integrity Protection (SIP)** which, by the way, rang the death knell for TotalFinder.

{% include inline-video.html %}

[Apps]({{ site.url }}{% link apps.md %}/){:.button .button-primary style="text-decoration: none;"}
