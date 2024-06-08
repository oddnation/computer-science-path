# 01. Pick a Language

The first part is picking a programming language, which is needed to learn and practice the Computer Science concepts, as there was a personal recommendation of picking either C++ or C due to dealing with pointers and memory allocation/deallocation. I decided to learn the Computer Science concepts with the [Zig programming language](https://ziglang.org/),  which is a "a general-purpose programming language and toolchain for maintaining **robust**, **optimal** and **reusable** software."

But seriously, why Zig? That is because by looking at the home page, it contains some great benefits as a pretty barebones language, which doesn't hold your hand when dealing with memory, *that* and it also has readable documentation. 

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