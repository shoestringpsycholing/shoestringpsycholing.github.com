---
layout: post
title: "NaBloPoMo and More Starting R"
date: 2012-11-01 20:22
comments: true
categories: R teaching misc
---
I'm using [NaBloPoMo](http://www.blogher.com/blogher-topics/blogging-social-media/nablopomo) as an excuse to kick-start this blog into a little more action.  Let's see if I can keep it up the whole month...

Today was the second session of an [R tutorial for beginners](http://shoestringpsycholing.github.com/blog/2012/10/25/starting-r/).  This one went a bit more smoothly, I think.  I'll update my work-in-progress [startR](https://github.com/shoestringpsycholing/startR) repo, if you're interested in the script.  I've done a few of these tutorial sessions now (for different audiences), and this one was the first time I really used an R script as a "script" in the more general sense of "scripted presentation."  In the past, I've had a kind of outline of things I want to cover, and I've usually run code, etc. to make sure things would work as expected beforehand, but when I'm actually in the middle of a tutorial, things inevitably go a little awry.  For me, usually in the form of annoying typos, in forgetting something or getting a little sidetracked, or sometimes even blanking on a particular function (last session I tried using `getwd()` and `setwd()`, but I rarely use those, and I was just sure they were `get.wd()` and `set.wd()`, and it totally threw me for a loop).

So this time I literally typed out every single thing in advance, in "walk-through" style, into a `.R` script, even things you'd normally never put in a script, like `head()` or `summary()`, and I think it really helped.  Not only did it save time and frustration by saving me from my inevitable typos, it helped me stay on track, and reminded me of all the little points I wanted to make, and the sequence in which I planned to make them.  

I didn't get a whole lot of immediate feedback, but people seemed to be following a little better, and in general the reaction seemed more positive. Of course, even the most effective demo or lecture is only the very beginning of the learning process.  But I think a clear demo, set up to be run as an actual walk-through, is a pretty efficient way to present a fair amount of code without getting people lost in the process of having to fix your own mistakes on the fly. And I think when you're presenting to a group of more than just a couple of people (I think there were at least 20 or so tonight), a clear demo is about the best you can hope for.
