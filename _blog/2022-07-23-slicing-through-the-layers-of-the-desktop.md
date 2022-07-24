---
title:  "Slicing Through the Layers of the Desktop"
date: 2022-07-23 12:00:00 +0002 # YYYY-MM-DD HH:MM:SS +/-TTTT
categories: synappser update
layout: blog
description: A sophisticated layered system of windows
---

![Slicing]({{ site.url }}/images/blog/Slicing.gif)

As you might guess, under the seemingly flat appearance of the Desktop lies a sophisticated layered system of windows that **AutoRaise** must take into account to efficiently perform its tasks.

```
Base Window                  # -2147483648
Minimum Window               # -2147483643
Desktop Window               # -2147483623
Desktop Icon Window          # -2147483603
Backstop Menu                # -20
Normal Window                # 0
Floating Window              # 3
Torn Off Menu Window         # 3
Modal Panel Window           # 8
Utility Window               # 19
Dock Window                  # 20
Main Menu Window             # 24
Status Window                # 25
Pop Up Menu Window           # 101
Help Window                  # 200
Dragging Window              # 500
Screen Saver Window          # 1000
Assistive Tech High Window   # 1500
Cursor Window                # 2147483630
Maximum Window               # 2147483631
```

Out of the twenty most common window layers, **AutoRaise** currently handles level 0 (i.e. Normal Window), carefully avoiding the others.

![Layers_1539x1225]({{ site.url }}/images/blog//Layers_1539x1225.png)

To answer the needs of some interesting feature requests, **AutoRaise** might start handling other layers in upcoming releases, so stay tuned.

{:.pt-2}
[Blog]({{ site.url }}{% link blog.md %}){:.button .button-primary style="text-decoration: none;"}