---
layout: post
title: A Reimplementation of NetBSD Using a Microkernel
date: 2016-01-31
tags: unix, netbsd, minix, microkernels
youtube: 0pebP891V0c
author: Andrew S. Tanenbaum
venue: BSDCan 2015
slides: http://www.slideshare.net/eurobsdcon/andy-tanenbaum-euro-bsdcon2014v2
---

###Abstract for talk:
This talk covers some of the history of Minix 3, what it is and why Andrew
started the project, and how after years of fighting it why he realized that
Minix 3 should be more like BSD than being its own thing.

He also talks a bit about some of the advantages Minix has by using a
Microkernel design rather than the more traditional monolithic kernel, such as
its self healing features (fault tolerance), which allows the system to detect
and recover from things like driver crashes automatically, as well as its
capability to be fully upgraded in place with no need to reboot the entire
system.

Lastly he goes into how at the userland Minix 3.3 is basically NetBSD, minus a
few of the more obscure system calls, why they chose NetBSD, and where they
currently stand on the project.

####About the Speaker: Andrew Tanenbaum
Andrew Stuart "Andy" Tanenbaum is an American computer scientist and professor
emeritus of computer science at the Vrje Universiteit, Amsterdam in the
Netherlands.  He is best known as the author of Minix a free Unix-like OS, that
runs off of a Mircokernel and has self healing (high fault tolerance).
