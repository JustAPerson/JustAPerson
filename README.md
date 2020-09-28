## Hi there 👋

I work full time as a backend software engineer at [Touchplan](https://touchplan.io), and I'm simultaneously attending my last semester at MIT working towards my BS in Computer Science.

### Computer Science Niche 🔍

I've been programming as a hobby for over ten years. From very early on, I discovered an interest in systems programming long before I knew the field had a name. I've always been curious about computers really work under all the layers of abstractions. This has lead me to explore a number of fascinating topics like compilers, operating systems, databases, and CPU microarchitecture. It feels like understanding all these abstractions and how they really work on the inside helps inform me on how to properly utilize them.

I'm really interested in problems of performance engineering because they're a good place where I can apply my knowledge and they can require a lot of creativity.

### What I'm Working on Lately 🔨

For the last year, my recreational programming efforts have been focused on [writing my own C compiler](https://github.com/denuocc/). Nearly 100 commits and many thousands of lines of code later, it's not anywhere near being finished, but I'm still having a lot of fun working on it when I can. I'm taking the time to get some of the core data structures and representations right, because as a solo project, it might be very difficult to go back and re-lay the foundation at a later time. One of the core features I've put a lot of care into is location tracking (recording where in the source code some feature of the program is derived from). On top of that, I've implemented the majority of the C preprocessor. These two features intersect in a nontrivial way: a location in C source code can have two different paths from which it derives. It can be expanded as a result of file inclusion (`#include <stdio.h>`) or macro expansion (`#define FOO`). This can make it really difficult to provide meaningful error messages, but I think I've finally gotten the right representation for this, and so now I've started working on a custom parser. With a lot of massaging, C can be parsed as an [`LL(2)`](https://en.wikipedia.org/wiki/LL_parser) language, but there are very few resources describing how to properly parse `LL(k)` languages where `k > 1`, so after scouring some ancient text books, I've managed to implement [this utility](https://github.com/JustAPerson/denuocc/tree/master/tools/grammar_tool) that simplifies the complicated task of writing any `LL(k)` parser.

<!--
**JustAPerson/JustAPerson** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
