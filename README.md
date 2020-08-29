# DiscoverBSD Talks
this is a source code for https://talks.discoverbsd.com website

 [![Build Status](https://travis-ci.org/DiscoverBSD/talks.svg)](https://travis-ci.org/DiscoverBSD/talks)

## About

DiscoverBSD Talks is a community based website where people can watch and discuss videos from BSD conferences, and thus learn.

As of now, new video is released every 2 weeks.

You might want to subscribe to get notified when new video is released (via [email](http://eepurl.com/bHOOKz) or [rss](https://talks.discoverbsd.com/feed.xml)).

## Community and contributing

People can recommend videos via GitHub's [PR](https://help.github.com/articles/using-pull-requests/) mechanism.  


### Example
Let's say you wanna recommend video called ["Early days of Unix and design of sh"](https://www.youtube.com/watch?v=FI_bZhV7wpI).

* [fork](https://github.com/DiscoverBSD/talks#fork-destination-box) the repo
* create an file inside `source/` dir named `{year}-{month}-{day}-{title}.html.markdown`, in our case `source/2016-01-01-early-days-of-unix-and-design-of-sh.html.markdown`
* feed the file with data
```
---
layout: post
title:  Early days of Unix and design of sh
date: 2016-01-01
tags: unix, sh
youtube: FI_bZhV7wpI
author: Stephen R. Bourne
venue: BSDCan 2015
slides: https://www.bsdcan.org/2015/schedule/attachments/306_srbBSDCan2015.pdf
---

### Abstract for talk:
- my history and background
- how and why we had to re write the shell
- why I wrote my own memory management
- key language design decisions
- where those ideas came from
- what was hard to get right
- system changes we made to accommodate sh
- what the rules were in UNIX group
- what would I do differently today

#### About the Speaker: Steve Bourne
Steve Bourne is computer scientist who is internationally known for his work on the UNIX operating system.  

While at Bell Laboratories, Steve designed the UNIX Command Language known as the "Bourne Shell". It is the standard command line interface to UNIX and is widely used today in scripting in the UNIX programming environment.  

Steve spent nine years at Bell Labs with the Seventh Edition Unix team. As well as the Bourne shell, he wrote the adb debugger and published /The UNIX System/, the second
book on the UNIX system, intended for a general readership. This book is recognized as a text for the effective use of UNIX.

```

Everything except `slides` is mandatory. Choose any date you want, it will be changed accordingly.

For setting **video** you have 2 choices: `youtube: FI_bZhV7wpI` for YouTube video or `vimeo: 12345675` for Vimeo video.


* push and create pull request

**Design and other PRs are welcome as well.**

###Some things to keep in mind in articles:
*  use only h3 and smaller (looks better in emails and so)
