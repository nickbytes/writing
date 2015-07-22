---
layout: post
title:  "Prototyping without CSS"
date:   2015-07-21 15:33:55
categories: basscss oocss prototyping
---
The ability to prototype quickly has been valuable for me at Hyperakt. I wish I would have put more time into my prototyping process earlier.

I work with daily with 5-10 designers at Hyperakt, each who use Adobe products. While I'm comfortable with these tools, I'm much more comfortable designing in my text editor/browser – I feel like you can flush out some short-comings in a design quicker as you play with different breakpoints rather than a static canvas.

One tool that is becoming indispensible to me for prototyping is OOCSS, and more specifically, [Basscss][basscss]. Why?

>Basscss lets me prototype without writing almost any CSS at all.

**Each class is a single-purpose class.**
This has stopped me from adding unneeded CSS cruft. I didn't realize how often I was writing `overflow: hidden;` for absolutely no reason. I've gained a deeper understanding of CSS because of it.

**(Perceived?) Greater content focus**
I've tricked myself into designing better for the content and experience, rather than creating a design and jamming my content in after the fact.

**Speed**
I don't need to set up Grunt or Gulp or Webpack or npm tasks for styles. If I want a super-quick, rough prototype, I can include the Basscss CDN link and start coding. I also don't have to switch back and forth between HTML/CSS files. As I write my markup, I style it accordingly.


[basscss]:      http://basscss.com
