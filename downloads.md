---
title: Downloads
layout: service
description: Downloads
---

{:.mb-1 style="font-size:0.75rem;"}
Apps are currently only signed with an Apple Development Certificate (without notarization). You will therefore get an *Application is damaged* or *Unidentified Developer* popup stating they *can't be opened*. Follow [Apple's instructions for opening an app from an unidentified developer](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unidentified-developer-mh40616/mac){:target="_blank"}{:rel="noopener noreferrer"} (select your OS version in the drop-down menu) to open either the application or its dmg for the first time.

{:.mb-1 style="font-size:0.75rem;"}
On **macOS Ventura** (up to macOS Sequoia 15.1), an additional step is needed where you go to System Settings > Privacy & Security and scroll down to Security. You'll find a note that the application was not opened because it is from an "Unknown Developer". Click "Open Anyway" then continue ignoring warnings and the program will work.

{:.mb-1 style="font-size:0.75rem;"}
On **macOS Sequoia 15.1** (and above), [Apple is forcing the notarization of applications](https://hackaday.com/2024/11/01/apple-forces-the-signing-of-applications-in-macos-sequoia-15-1/){:target="_blank"}{:rel="noopener noreferrer"}. A few workarounds are however still available. Depending on your familiarity with running shell commands, you could use one of the following solutions:
- **xattr -rd com.apple.quarantine /Applications/FinderFix.app** (e.g. disables gatekeeper for FinderFix).
- **sudo spctl --master-disable** (requires your administrator password and disables gatekeeper permanently).
- **Drag and drop** the application into the free [Sentinel.app](https://itsalin.com/appInfo/?id=sentinel){:target="_blank"}{:rel="noopener noreferrer"} to remove quarantine.
{:.mb-1 style="font-size:0.75rem;"}

**If you are enjoying my applications, consider giving them a star on [GitHub](https://github.com/synappser){:target="_blank"}{:rel="noopener noreferrer"}**. It would be great if you could also share your experience through forums or talk about them on your regular social media channels to help spread the word about their benefits. Thank you!


{:#top-anchor}
**IMPORTANT** - [Read this legal note carefully before downloading any of the following beta apps](#legal-anchor).

## FAQ

#### Are these apps pre-releases?

Yes, they are currently in public beta.

#### Are they free to download?

Yes, they are free while in beta.

# FinderFix

| System Requirements |
| ------------------- |
| Apple silicon or Intel processor |

| Version | Download | Release notes | Minimum OS|
| ------- | -------- | ------------- | ----------|
 v0.7.5 | [Public Beta](https://github.com/synappser/FinderFix/releases/download/v0.7.5/FinderFix_v0.7.5b.dmg) | [Release notes]({{ site.url }}{% link releases/finderfix_v0.7.5.md %}) | macOS 11.0 |
| v0.7.4 | Public Beta| [Release notes]({{ site.url }}{% link releases/finderfix_v0.7.4.md %}) | macOS 11.0 |
| v0.7.3 | Public Beta | [Release notes]({{ site.url }}{% link releases/finderfix_v0.7.3.md %}) | macOS 11.0 |
| v0.7.2 | Public Beta | [Release notes]({{ site.url }}{% link releases/finderfix_v0.7.2.md %}) | macOS 10.15 |
| v0.7.1 | Public Beta | [Release notes]({{ site.url }}{% link releases/finderfix_v0.7.1.md %}) | macOS 10.14.6 |
| v0.6.7 | Public Beta | [Release notes]({{ site.url }}{% link releases/finderfix_v0.6.7.md %}) | macOS 10.14.6 |
| v0.5.9 | Public Beta | [Release notes]({{ site.url }}{% link releases/finderfix_v0.5.9.md %}) | macOS 10.13 |

{:.pt-1}
# AutoFocus

| System Requirements |
| ------------------- |
| Apple silicon or Intel processor |

| Version | Download | Release notes | Minimum OS|
| ------- | -------- | ------------- | ----------|
| v0.7.0 | [Public Beta](https://github.com/synappser/AutoFocus/releases/download/v0.7.0/AutoFocus_v0.7.0b.dmg) | [Release notes]({{ site.url }}{% link releases/autofocus_v0.7.0.md %}) | macOS 11.0 |
| v0.6.9 | Public Beta | [Release notes]({{ site.url }}{% link releases/autofocus_v0.6.9.md %}) | macOS 11.0 |
| v0.6.8 | Public Beta | [Release notes]({{ site.url }}{% link releases/autofocus_v0.6.8.md %}) | macOS 11.0 |
| v0.6.7 | Public Beta | [Release notes]({{ site.url }}{% link releases/autofocus_v0.6.7.md %}) | macOS 11.0 |
| v0.6.6 | Public Beta | [Release notes]({{ site.url }}{% link releases/autofocus_v0.6.6.md %}) | macOS 10.14.6 |
| v0.6.2 | Public Beta | [Release notes]({{ site.url }}{% link releases/autofocus_v0.6.2.md %}) | macOS 10.13 |

{:.pt-1}
# Taskan

| System Requirements |
| ------------------- |
| Apple silicon or Intel processor |

| Version | Download | Release notes | Minimum OS|
| ------- | -------- | ------------- | ----------|
| v0.3.4 | [Public Beta](https://github.com/synappser/Taskan/releases/download/v0.3.4/Taskan_v0.3.4b.dmg) | [Release notes]({{ site.url }}{% link releases/taskan_v0.3.4.md %}) | macOS 11.0 |
| v0.3.3 | Public Beta | [Release notes]({{ site.url }}{% link releases/taskan_v0.3.3.md %}) | macOS 11.0 |
| v0.3.2 | Public Beta | [Release notes]({{ site.url }}{% link releases/taskan_v0.3.2.md %}) | macOS 11.0 |
| v0.3.1 | Public Beta | [Release notes]({{ site.url }}{% link releases/taskan_v0.3.1.md %}) | macOS 11.0 |

{:.pt-1}
# TrashEye

| System Requirements |
| ------------------- |
| Apple silicon or Intel processor |

{:.mt-n1}
**New!** TrashEye now has a BetterTouchTool Touch Bar companion trash can widget that, beyond showing the number of trashed items, allows you to open the local trash bin by touching the widget's icon.

{:.mt-n3}
![Companion Widget]({{ site.url }}/images/apps/companion-widget.gif)

{:.mt-n3}
**[Download the companion widget](https://github.com/synappser/Companion/releases/download/v1.0/Companion_v1.0.zip?raw=true)** (installation instructions in the zip file)

| Version | Download | Release notes | Minimum OS|
| ------- | -------- | ------------- | ----------|
| v0.5.5 | [Public Beta](https://github.com/synappser/TrashEye/releases/download/v0.5.5/TrashEye_v0.5.5b.dmg) | [Release notes]({{ site.url }}{% link releases/trasheye_v0.5.5.md %}) | macOS 11.0  |
| v0.5.4 | Public Beta | [Release notes]({{ site.url }}{% link releases/trasheye_v0.5.4.md %}) | macOS 11.0  |
| v0.5.3 | Public Beta | [Release notes]({{ site.url }}{% link releases/trasheye_v0.5.3.md %}) | macOS 11.0  |
| v0.5.2 | Public Beta | [Release notes]({{ site.url }}{% link releases/trasheye_v0.5.2.md %}) | macOS 10.14.6 |
| v0.4.9 | Public Beta | [Release notes]({{ site.url }}{% link releases/trasheye_v0.4.9.md %}) | macOS 10.13 |

{% include legal-note.html %}{:.mt-6}

[back to top](#top-anchor)

{:.pt-4}
[Apps]({{ site.url }}{% link apps.md %}){:.button .button-primary style="text-decoration: none;"}
