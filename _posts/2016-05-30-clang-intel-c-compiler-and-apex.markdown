---
layout: post
title: "Clang, Intel C Compiler and APEX"
date: "2016-05-30 22:40:41 +0200"
---

Now Harvey is being built with clang and icc.

 Though work on gcc port is in progress.
 This means that clang is scheduled now to be ported.
 Thanks to Ron Minnich, Harvey can be built with icc now as a third toolchain. Always trying to keep the code
 more portable as possible.

APEX is released.

 We imported many things from [musl libc](https://www.musl-libc.org/).
 Now a new stdio and others are available, improving the works on gcc and clang ports.
 There are still some parts pending to be included, like musl complex and stdioext code. Trying to do the software porting tasks easier.
 You can take a look at [its repo](https://github.com/Harvey-OS/apex) and [its wiki](https://github.com/Harvey-OS/apex/wiki).
 Also we are using clang to build APEX now.

FS project.

 We started to work on some FS alternative to fossil, looking for a main file system for Harvey, though we still use fossil for disks.

If you are interested in something of this or in start a new project, just tell us about it in our [list](http://groups.google.com/forum/#!forum/harvey).
