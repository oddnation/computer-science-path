# 01. Pick a Language

The first part is picking a programming language, which is needed to learn and practice the Computer Science concepts, as there was a personal recommendation of picking either C++ or C due to dealing with pointers and memory allocation/deallocation. I decided to learn the Computer Science concepts with the [Zig programming language](https://ziglang.org/),  which is a "a general-purpose programming language and toolchain for maintaining **robust**, **optimal** and **reusable** software."

But seriously, why Zig? That is because by looking at the home page, it contains some great benefits as a pretty barebones language, which doesn't hold your hand when dealing with memory, *that* and it also has readable documentation. 

#### Learning Resources:
* [Getting started](https://ziglang.org/learn/getting-started) found on the ziglang website
* [Zig.guide](https://zig.guide/) by [Sobeston](https://github.com/Sobeston/zig.guide)
* [Ziglings](https://codeberg.org/ziglings/exercises/)
* [Zig on Exercism](https://exercism.org/tracks/zig)
* [Learning Zig](https://www.openmymind.net/learning_zig/) by [karlseguin](https://github.com/karlseguin)
* [Code Examples](https://ziglang.org/learn/samples/#using-curl-from-zig) of zig being used from memory leak detection to using cURL from Zig

#### Additional Resources:
* [Zig Build System](https://ziglang.org/learn/build-system/)
* [In-depth Overview](https://ziglang.org/learn/overview/)
* [Why Zig When There is Already C++, D, and Rust?](https://ziglang.org/learn/why_zig_rust_d_cpp/)
* [List of tools](https://ziglang.org/learn/tools/) which are useful to write Zig code
* [Road to Zig 1.0](https://www.youtube.com/watch?v=Gv2I7qTux7g) by [Andrew Kelley](https://andrewkelley.me/) President and Lead Developer of [Zig Software Foundation](https://ziglang.org/zsf/)
* [Zig's New Relationship with LLVM](https://kristoff.it/blog/zig-new-relationship-llvm/)
* [Language Reference](https://ziglang.org/documentation/master/)
* [Standard Library Documentation](https://ziglang.org/documentation/master/std/)

## What Zig promises:
### ⚡ A Simple Language
Focus on debugging your application rather than debugging your programming language knowledge.
- No hidden control flow.
- No hidden memory allocations.
- No preprocessor, no macros.

### ⚡ Comptime
A fresh approach to metaprogramming based on compile-time code execution and lazy evaluation.
- Call any function at compile-time.
- Manipulate types as values without runtime overhead.
- Comptime emulates the target architecture.

### ⚡ Maintain it with Zig
Incrementally improve your C/C++/Zig codebase.
- Use Zig as a zero-dependency, drop-in C/C++ compiler that supports cross-compilation out-of-the-box.
- Leverage `zig build` to create a consistent development environment across all platforms.
- Add a Zig compilation unit to C/C++ projects, exposing the rich standard library to your C/C++ code.