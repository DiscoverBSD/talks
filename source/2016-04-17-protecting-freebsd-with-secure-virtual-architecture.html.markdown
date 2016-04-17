---
layout: post
title: Protecting FreeBSD with Secure Virtual Architecture
date: 2016-04-17
tags: FreeBSD, security
youtube: hRIC_aF_u24
author: John Criswell
venue: BSDCan 2015
---

###Abstract for talk:

In this talk, I will present our work on using the Secure Virtual Architecture (SVA) to protect FreeBSD applications and the FreeBSD kernel from security attacks. SVA is an LLVM-based infrastructure that permits us to use compiler instrumentation techniques to enforce security policies on both application and kernel code. In this talk, I will briefly describe how we used SVA to implement KCoFI: a system that enforces control-flow integrity and code segment integrity on the FreeBSD kernel to protect it from control-flow hijack attacks. I will then describe how we extended KCoFI to build Virtual Ghost. Virtual Ghost protects applications from a compromised operating system kernel. I will describe how Virtual Ghost uses compiler instrumentation to prevent the FreeBSD kernel from spying on and corrupting private application data and how it prevents the kernel from maliciously modifying application control flow (while still supporting features such as signal handlers and process creation).


####About the Speaker: John Criswell
John Criswell is an assistant professor in the Department of Computer Science at the University of Rochester. His research interests are computer security, operating systems, and compilers.

John Criswell is an assistant professor in the Department of Computer Science at the University of Rochester. He earned both his B.S. in Computer Science (2003) and Ph.D. in Computer Science (2014) at the University of Illinois at Urbana-Champaign.

John’s research interests focus on computer security and novel applications of compiler and operating system technology. John's primary research work is on the Secure Virtual Architecture (SVA). SVA enforces security policies on commodity operating system and application code via compiler instrumentation, thereby providing strong protection against sophisticated attacks. Using SVA, John built the first systems that provide strong automated memory safety protection and complete control-flow integrity enforcement to commodity operating system kernels such as Linux and FreeBSD. More recently, John has used SVA to create the Virtual Ghost system that protects application data and control-flow from a compromised operating system kernel.

Prior to joining the University of Rochester, John was a research programmer and graduate student at the University of Illinois. Before that, John worked at Argus Systems Group, Inc. John’s work at Argus Systems Group included enhancements to the AIX operating system kernel and writing utilities that utilized mandatory access controls to improve system security.
