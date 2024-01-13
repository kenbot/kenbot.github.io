---
title: Lenses for the masses - introducing Goggles
video_url: https://www.youtube.com/watch?v=t2WTtIwgdLc
embed_url: https://www.youtube.com/embed/t2WTtIwgdLc
year: 2017
minutes: 36
host: Typelevel Summit, YOW! Lambda Jam
code: https://github.com/kenbot/goggles
tags: 
- FP
- lenses
- optics
- code
---
Lenses, or more generally optics, are a technique that is indispensable to modern functional programming. However, implementations have veered between two extremes: incredible abstractive power with a steep learning curve; and limited domain-specific uses that can be picked up in minutes. Why can't we have our cake and eat it too? 

Goggles is a new Scala macro built over the powerful & popular Monocle optics library. It uses Scala's macros and scandalously flexible syntax to create a compiler-checked mini-language to concisely construct, compose and apply optics, with a gentle, familiar interface, and extravagantly informative compiler errors. In this talk I'll introduce the motivation for lenses and why usability is a problem that so badly needs solving, and how the Goggles library, with Monocle, helps address this in an important way. There'll be some juicy discussion of Scala macro sorcery too!