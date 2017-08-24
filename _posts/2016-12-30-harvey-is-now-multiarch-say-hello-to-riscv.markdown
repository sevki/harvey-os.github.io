---
layout: post
title: "Harvey is now multiarch: say hello to RISC-V"
date: "2016-12-30 22:44:46 +0200"
---
Ending this year, Ron G. Minnich has got Harvey running in [RISC-V](https://riscv.org/) architecture, booting Harvey on [Spike (ISA Simulator)](https://riscv.org/software-tools/risc-v-isa-simulator/) and running rc shell on it. But he never rests and now is working on bringing it to QEMU and to FPGA.
It's a big step for Harvey because we fixed some multiarch issues across the source and Ron found some bugs in timer interrupts in the hardware,
so we all learned something.
