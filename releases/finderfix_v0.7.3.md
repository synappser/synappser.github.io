---
title: "FinderFix"
version: "0.7.3"
date: "Sep 10, 2023"
image: "images/apps/finderfix.png"
layout: release
---

- Change the Locale parsing algorithm to better identify language and region codes, making it flexible enough to distinguish between Portuguese (Portugal) and Portuguese (Brazil) and still robust enough for a fall-through when the operating system does not contain localizations for the specific region
- Fix .DS_Store removal still running after checkbox has been unticked
- Add optional system-wide removal of .DS_Store files in Home and Applications directories and subdirectories
- Add "Go to Folder" (Shift-Cmd-G) to the exclusion list
- Minimum OS requirements: 11.0

<br />

{:.pt-2}
[Downloads]({{ site.url }}{% link downloads.md %}){:.button .button-primary style="text-decoration: none;"}
