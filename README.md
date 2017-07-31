# BASM

## Bootstrapping Assembler

### Goal

The goal of this project is to create a working assembler (starting with the
ARMv8 architecture) that is able to assemble it's own source code and, at least,
the source of its next iteration.

### Why?

For funsies?

### References

This idea came to me from several things:

1. Playing with some of the low-level stuff in University CS classes.
1. [“Reflections on Trusting Trust”](https://www.ece.cmu.edu/~ganger/712.fall02/papers/p761-thompson.pdf) and [“Countering ‘Trusting Trust’”](https://www.schneier.com/blog/archives/2006/01/countering_trus.html) (the latter of which helped me understand what was going on, but the former which got me interested in how source turns into machine instructions and data).
1. [“Bootstrapping a simple compiler from nothing”](https://web.archive.org/web/20061108010907/http://www.rano.org/bcompiler.html) (I read through the article a couple times but haven't looked at the source, but I think I'm going to use the same strategy of providing a history of iterations (using git) and verifiable sources and binaries).
