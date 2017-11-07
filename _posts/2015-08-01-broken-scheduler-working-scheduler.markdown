---
layout: post
title: "Broken scheduler, working scheduler"
date: "2015-08-01 22:35:01 +0200"
---
Despite the hot summer, Harvey has been progressing steadily during these months. So, a big THANK YOU to everyone involved, you all rock!

Obviously, it can't all be happy days: resident guru Aki Nyrhinen has just proved how things can easily fall into chaos by detecting a major defect in Harvey's core. Straight from the horse's mouth:

* it turns out that the scheduler in harvey is badly broken.
* it does not do time sharing at all, among other things.
* it also crashes instantly if squidboy is enabled (* 1 core).
* the procs aren't really reusable at all, because the kernel structures are apparently infested with pointers to the procs when one does an exit.
* there's a lot to be fixed here.

Undeterred by the mess, and in a question of hours, the fire has been put out:

* Alright, after 4 hours of furious editing and undoing damage to the boot code, I've got harvey booting up with the ndnr() in squidboy commented out.

Some (thorough?) measurements after the fix:

* Boot faster.
* CPU at 13% as usual (we still have pending a new random).
* No weird behaviours.
* Nice job!

Hooray!
