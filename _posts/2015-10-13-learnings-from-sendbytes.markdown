---
layout: post
title:  "Learnings from Sendbytes"
date:   2015-10-13 10:25:55
categories: react js sendbytes
---

I recently created [Sendbytes][sendbytes], a goofy e-greeting card site.

It's a project I had been thinking about for a while, and I was excited to find out I would get the opportunity to try out a few technologies like React Router, more advanced webpack configurations, style loaders, and basscss... etc etc.

Here are a few less technical things I learned.

* **Say 'no' to yourself every once in a while**
  * URLs are a little nasty looking in this project. I could have taken the time to create this project using Node.js, created user accounts and authentication, then used Bit.ly API to give everyone unique URLs based on their account, but then there's some security concerns maybe? ... This gets out of hand quickly.
  * This would have taken forever, and greatly increased chances of me not completing the project at all. None of that is really necessary.
  * Solution: use URL routing, skip the backend (avoids privacy concerns since any message is possible).

* **Tell a few friends about your project right when you start**
  * It's tough to complete projects outside of work. There's little accountability when you're the only person who knows about the project. I told a few people about the project and when I expected to be done – in return, they asked me about how the project was going, what tools I was using, how prototyping was going, and whether I felt like I was going to make my designated date. It was like having a friendly stand-up meeting. I felt accountable to them and didn't let myself wane.
  * They also ended up being the first users and great testers!
* **Sloppy is okay at the beginning**
  * The codebase is a little bit of a mess. That makes me anxious. What if people look at this now? Will they think I'm a terrible developer? I mixed embedded and inline styles. I repeated myself a ton. My webpack setup could be much nicer, I didn't even use the hot-loader the way most people do. My naming is horrible.
  * This doesn't really matter at this stage of the project. I'm not sure how long I will maintain this or where the project will go from here. There's no technical debt created if I never touch this again. If I find out that I want to continue with this project, then I'll address some of those concerns. If someone else joins the project, I can clean up the codebase. **Done is better than perfect.**

  [Thanks for reading.][thanks]




[sendbytes]:      http://sendbytes.space
[thanks]:     http://sendbytes.space/#/final/1/cmVhZGluZyBteSBjcmF6eSBibG9nIHBvc3QgYWJvdXQgdGhpcyBzaXRlLg==/Tmljaw==
