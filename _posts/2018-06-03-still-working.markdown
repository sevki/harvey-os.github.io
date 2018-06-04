---
layout: post
title: "Still here and working"
date: "2018-06-03 11:00:41 +0200"
---

It's been a while since the last time we posted anything in our website. But does not means we abandoned the project, we were working silently trying to improve Harvey along all this time.
All you know the big problem with opensource projects: free time for doing it. And our team is not an exception. We dedicate to Harvey all the time we can, and due to lack of free time, stretching targets by priority for not wasting that precious time we spend in it.

We fixed bugs, some of them very importants like stack alignment in processes or usb keyboard and mouse drivers. We began the port of FreeBSD UFS2 file system, until the point of making possible to read an UFS partition, but not for using it as the main file system for Harvey yet. During the development, bugs and some surprises rised and we had to solve them by the way, stopping main tasks over the system.
The GCC port is still in progress, APEX has been fixed many times while native port of GCC was going forward. The bootstrap is still failing due to problems in APEX library, which is the main part in all of this.

At this point we're working in a bootable image, usb and virtual QEMU disk, based for now in Fossil and Venti. We think this could be a nice and alternative way for tasting Harvey, maybe better known for many people than building it or using the Docker image.

Harvey is still alive and we have still illusion. Every hand, we said many times, is always welcome.
