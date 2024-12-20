---
title: "FinderFix"
version: "0.7.5"
date: "Dec 23, 2024"
image: "images/apps/finderfix.png"
layout: release
---

- Add a workaround for localizable strings on macOS 15 (Sequoia) while still making all recent features available (as a temporary solution until I can debug the crash on a system running Sequoia). The system Locale must be set to English on Sequoia if you want to use the special windows exclusion list (i.e. "Info", "Quick Look", "Copy", "Connect to Server...", "Go to Folder...").

<br />

{:.pt-2}
[Downloads]({{ site.url }}{% link downloads.md %}){:.button .button-primary style="text-decoration: none;"}
