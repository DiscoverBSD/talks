---
layout: post
title: Open/LibreSSL in FreeBSD
date: 2016-07-03
tags: openssl, libressl, freebsd
youtube: JGgoBQ0hVpw
author: Bernard Spil
venue: BSDCan 2016
slides: https://www.bsdcan.org/2016/schedule/attachments/373_State%20of%20LibreSSL%20in%20FreeBSD%20ports%20and%20base.pdf
---

###Abstract for talk:

This talk will address the changes required to ports to deal with the changes that LibreSSL introduced (and keeps introducing). Additionally I will talk about the support-lifecycle of both the LibreSSL and OpenSSL projects and the impact on operating systems and other software projects. Lastly I will address making OpenSSL in base private and/or replacing FreeBSD's base OpenSSL with LibreSSL.

Following the Heartbleed vulnerability OpenBSD forked OpenSSL into LibreSSL. The portable version of LibreSSL was ported to FreeBSD a day after it was released causing a large number of problems with ports. Meanwhile OpenSSL changed its support-lifecycle and will stop supporting current versions very soon. LibreSSL is being actively developed which induces more changes to ports.

The PC-BSD project ran an 'EDGE' build of their packages with LibreSSL which surfaced a number of problems with major ports like Python, OpenLDAP and Apache. After the first major ports were fixed the build surfaced ca 100 packages failing to build for various reasons. I will show some examples of these problems and fixes for them. With the release of LibreSSL 2.3 came the removal of SSLv3. This caused another ca 100 ports to fail due to hard dependencies on SSLv3 methods in the libraries. Again some major ports where affected. I will show an example of this issue and the proper solution to it.

Additionally, there are ports that are not linking the desired OpenSSL libraries. Even when WITHOPENSSLPORTS is defined they link to the libraries in /usr/lib. Work is underway trying to make the OpenSSL libraries in base 'private' libraries. I will show the work performed and the effects on a system.


####About the Speaker: Bernard Spil

Read about him at https://wiki.freebsd.org/BernardSpil. 
