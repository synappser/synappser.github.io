---
title: "TrashEye"
date: 2018-11-19T10:47:58+10:00
draft: false
image: "images/apps/trasheye.png"
intro_image: "images/screencasts/03-te-video.mp4"
intro_image_preview: "images/screencasts/03-te-preview.png"
intro_image_absolute: true
intro_image_hide_on_mobile: true
jobtitle: "Utilities"
linkedinurl: "https://www.linkedin.com/"
promoted: true
weight: 3
layout: app
---

**Simply a Trash Can on your Desktop**

With my laptop's small display, I have Dock-hiding always turned on; anyway the trash icon doesn't show the file count and a quick Command-Option-D brings it back. Like many of you, I got used to the Trash Can on the Desktop with DragThing that I later replaced with Bin-it until the latter was also discontinued. Lately, I even tried iCollections' Trash pane without much success. Some of you may have even know the original Mac OS 9 trash can!

<!--break-->

However, all of these were not real-time, sometimes taking several seconds to refresh their content. If I remember correctly, Bin-it was even limited to the local Trash (i.e. the ~/.Trash folder). What's more with my bad eyesight, I needed a big red badge for the total count (the typical Apple NSColor.red for badges), in order to not have to stare for long seconds at the icon to read its count. I am quite obsessive about not deleting something by mistake, and assume others are like me, that's the reason for the big red badge.

![Real Time Refresh]({{ site.url }}/images/apps/real-time-refresh.gif){:.quarter-width}

What's remarkable about **TrashEye** is its real-time refresh rate. It also has practically zero impact on both CPU and memory.

{:.pb-1 .mt-1 .sub-heading}
## Companion Widget

TrashEye now has a BetterTouchTool Touch Bar companion trash can widget that, beyond showing the number of trashed items, allows you to open the local trash bin by touching the widget's icon.

![Companion Widget]({{ site.url }}/images/apps/companion-widget-cropped.gif)

**[Download the widget](https://github.com/synappser/Companion/releases/download/v1.0/Companion_v1.0.zip?raw=true)** (installation instructions in the zip file)

{:.pb-1 .mt-1 .sub-heading}
## Features

- Sliding the switch to On in the Preferences window, displays a Trash icon in the bottom left corner of your Desktop
- A single click (left-click) on TrashEye's icon opens the Bin folder
- Right-clicking on the Trash Can opens a contextual menu
- To reposition the Trash on your Desktop click the Reposition Trash menu item. This action will reveal its background view, allowing you to grab it and move it to your liking
- "Force Empty Trash" deletes locked files. It auto-detects if Touch ID is enabled for sudo and adapts its strategy accordingly (see below for a Howto):

    [How to enable Touch ID for sudo on MacBook Pro](https://azimi.io/how-to-enable-touch-id-for-sudo-on-macbook-pro-46272ac3e2df){:target="_blank"}{:rel="noopener noreferrer"}

    [Can Touch ID for the Mac Touch Bar authenticate sudo users and admin privileges?](https://apple.stackexchange.com/questions/259093/can-touch-id-for-the-mac-touch-bar-authenticate-sudo-users-and-admin-privileges){:target="_blank"}{:rel="noopener noreferrer"}
- Dragging items on to TrashEye's Desktop icon adds them to the trash
- Dragging installer volumes to TrashEye's Desktop icon ejects them

{:.pt-4}
[Apps]({{ site.url }}{% link apps.md %}){:.button .button-primary style="text-decoration: none;"}
