---
layout: post
title: Unifying jail and package management for PC-BSD, FreeNAS and FreeBSD
date: 2016-06-19
tags: jail, package, freenas, freebsd, pc-bsd
youtube: qNYXqpJiFN0
author: Kris Moore
venue: BSDCan 2015
slides: https://www.bsdcan.org/2015/schedule/attachments/291_appcafe-talk2015.odt
---

###Abstract for talk:

Historically the PC-BSD project has had easy-to-use, powerful GUI utilities for package and jail management. However, being X11/Qt applications, this made their usefulness limited only to workstations, or other systems running a graphical environment, not particularly well suited for FreeNAS or a traditional FreeBSD server. With the rise of web-browser driven system management, it was also time for PC-BSD to begin converting some of its more popular tools into web-manageable forms.

Over the summer of 2014, a new project was started to re-create the AppCafe, a pkgng front-end, and the Warden, a jail manager, into web-accessible utilities for inclusion into both PC-BSD and FreeNAS. This front-end allows remote management of jails and packages on the upcoming FreeNAS 10, as well as system package management on FreeBSD and PC-BSD. This talk will provide a high-level overview of the functionality of the new AppCafe / Warden, along with technical details about the implementation for developers.

####About the Speaker: Kris Moore

Kris Moore is the founder of the PC-BSD project, and co-host of the BSDNow video podcast.

Kris Moore is the founder and lead developer of the PC-BSD project. He is also the co-host of the popular BSDNow video podcast. When not at home programming, he travels around the world giving talks and tutorials on various BSD related topics at Linux and BSD conferences alike. He currently lives in Tennessee (USA) with his wife and five children and enjoys playing bass guitar / video gaming in his (very limited) spare time.
