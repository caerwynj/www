# caerwyn.com
From 2004 I focused on operating systems from Bell Labs including Unix, Plan 9, and Inferno OS.  I hosted a blog about Inferno OS called the [Inferno Programmer's Notebook](http://ipn.caerwyn.com). I stopped working on Inferno OS around 2012. Most developers in the community moved over to the Go language around that time.  However, since 2022 I haved worked on Inferno OS again, porting it to the Raspberry Pi Pico, porting it to 64 bit platforms, and building inferno compute clusters.  Check out the repositories below. The Inferno OS is now considered "retro". I still enjoy it because I can self-host such a flexible system. I like the Limbo language. And many interesting opportunities still await such a small and elegant OS.

## Blog
* [Inferno Programmer's Notebook](http://ipn.caerwyn.com)
* [Archimedes Programmer's Notebook](https://caerwynj.github.io/archimedes-lab/). Presenting algorithms from Knuth's "The Art of Computer Programming" in Archimedes Assembly (ARM3).
* [Medium Essays](https://medium.com/@caerwynj) A few essays on AI.
* [Inferno64 cluster microblog](https://x.com/caerwy). I microblog my progress building an Inferno64 cluster using reclaimed hardware such as old smartphones.

## Repositories
* [Inferno Lab](https://github.com/caerwynj/inferno-lab). Source code for all the prototype software made in the Inferno operating system over a number of years. Much of it is written in the Limbo programming language, a precursor to Go. It had excellent support for communicating sequential processes much like Go.
* [Acme SAC](https://github.com/caerwynj/acme-sac). The Acme editor was developed by Rob Pike for the Plan 9 operating system. It was ported to Inferno OS by VitaNuova.  Made into  a "standalone" editor for Windows and other operating systems by packaging and customizing the editor and Inferno OS. The original Acme editor is part of [Plan 9 from user space](https://9fans.github.io/plan9port/) port to Unix like systems and I recommend you use that version.
* [Docker Images](https://hub.docker.com/u/caerwyn). Docker images for Inferno and Acme-SAC.
* [Inferno OS on Raspberry Pi Pico](https://github.com/caerwynj/inferno-os/tree/pico).  Inferno OS ported to the Raspberry Pi Pico using the GCC toolchain and PICO SDK.
* [Inferno64](https://github.com/caerwynj/inferno64). A port of inferno OS to 64 bit platforms amd64 and arm64 with JIT compilers.
