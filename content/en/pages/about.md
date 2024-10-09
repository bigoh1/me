---
title: About me
description: "about me page"
author: Yehor Varbanskyi
math: true
date: 2024-10-09
---

Hi! :heart:

My name is Yehor<sup><a id="footnote-1-ref" href="#footnote-1">1</a></sup>. I'm <span id="myage"></span> y.o. I'm originally from :ukraine:, but I'm of Bulgarian descent, so I moved there permanently to reunite with the historical homeland of my ancestors.

Currently studying Mathematics at Sofia University «St. Kliment Ohridski», FMI.

I've been fascinated by computers for as long as I can remember; wrote my first line of code at the age of 12, and have been hooked ever since. Along the way, I've discovered that my true passion is intellectual challenge – which naturally led me to Theoretical Computer Science and Math.

What I'm into these days:
- (distributed) algorithms and data structures
- functional programming (learning Haskell atm), type theory
- compilers
- computational complexity theory, theory of computation
- anything related to _pure_ math
- neovim, linux, typst 
- law


<!--
  draft info for me:
- book nerd

      TODO: add somewhere my English teaching experience and maybe a page or two for my students (mb also add a preview video of my accent?; add IELTS certificate); think about making this accessible only by link – without displaying on the website itself
      TODO: create a list-page for my repos/projects/portfolio, that will look similar to Posts/, but have little preview's next to them. For sure will require some tweaking of the theme internals.
      TODO: add page (like Posts/) with my link dump

  -->

## Footnotes

<!--
    TODO: when I become proficient enough in Hugo, turn this footnote stuff into my forked theme.
    And probably use hugo's (inline) shortcuts for that
-->
<p id="footnote-1">
   1. pronounced as Yegor <a href="#footnote-1-ref">&#8617;</a> 
</p>

<script>
    // this is _close_ to my birthday, but not exactly it
    // why are you even here?? :]
    var myage = Math.floor((new Date() - new Date("2005-06-29").getTime()) / 3.15576e+10) 
    document.getElementById('myage').textContent = myage;  
</script>
