# DiscoverBSD Talks
this is a source code for https://talks.discoverbsd.com website

 [![Build Status](https://travis-ci.org/DiscoverBSD/talks.svg)](https://travis-ci.org/DiscoverBSD/talks)

##About

DiscoverBSD Talks is a community based website where people can watch and discuss videos from BSD conferences, and thus learn.

As of now, new video is released every 2 weeks.

You might want to subscribe to get notified when new video is released (via [email](http://eepurl.com/bHOOKz) or [rss](https://talks.discoverbsd.com/feed.xml)).

##Community and contributing

People can recommend videos via GitHub's [PR](https://help.github.com/articles/using-pull-requests/) mechanism.  


###Example
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
video: FI_bZhV7wpI
author: Stephen R. Bourne
venue: BSDCan 2015
slides: https://www.bsdcan.org/2015/schedule/attachments/306_srbBSDCan2015.pdf
published: false
---

###Abstract for talk:
- my history and background
- how and why we had to re write the shell
- why I wrote my own memory management
- key language design decisions
- where those ideas came from
- what was hard to get right
- system changes we made to accommodate sh
- what the rules were in UNIX group
- what would I do differently today
```
Everything except `slides` is mandatory. Choose any date you want, it will be changed accordingly.

* push and create pull request

**Design and other PRs are welcome as well.**

###Some things to keep in mind in articles:
*  use only h3 and smaller (looks better in emails and so)
