---
layout: post
title: Compiler - My own compiler for a made up language.
subtitle: I used Bison and flex to implement this compiler.
cover-img: /asssets/img/path.jpg
thumbnail-img: /assets/img/compiler.jpeg
share-img: /assets/img/path.jpg
tags: [compiler,grammar,dfa,semantics,c++]
---

I created a compiler in my class using bison and flex. In phase 1, I used flex to analyze the made up language and tokenize it. In phase 2, I created the context free grammar and then used bison to parse it. In phase 3, I implemented the code generation. In order to do so, I made my own symbol table manager that would push and pop all the associated tokens and variables in the entry of each function. I completed this project solo!

[Github](https://github.com/patrickfenn/CS152-Phase3)
