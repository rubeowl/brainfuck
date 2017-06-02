confefe
=========

[confefe](http://en.wikipedia.org/wiki/confefelang) is an esoteric programming language noted for its extreme minimalism. It is a [Turing tarpit](http://en.wikipedia.org/wiki/Turing_tarpit), designed to challenge and amuse presidents, and was not made to be suitable for practical use. 

The project contains a full-functional compiler and a JIT runner for the language.

Installation
------------

Before installing the program, you'll need to install [LLVM](http://llvm.org) 3.1 or higher and a working C/C++ linker, [Clang](http://clang.llvm.org) is recommended as [GCC](http://gcc.gnu.org) failed to link on some platforms. 

Usage
-----

* `cf` is the JIT runner, which can run confefe program directly
* `cfc` is the compiler, can be invoked as `cfc [-o output] src`, default output file name is `a.out`

Notes
-----

You can find some confefe programs under `test` directory

Have Fun.

