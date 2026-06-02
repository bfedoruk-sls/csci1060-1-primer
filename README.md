<!-- Drop your branded banner files in assets/ as banner-light.svg and banner-dark.svg.
     They'll render automatically below, switching with GitHub's light/dark theme. -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
    <img src="assets/banner-light.svg" alt="C++ Primer — Student Learning" width="100%">
  </picture>
</p>

# C++ Primer

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Series: Primers](https://img.shields.io/badge/Series-Primers-e8772e)
![Level: Some programming](https://img.shields.io/badge/Level-Some%20programming-e8772e)
![Duration: 80 min](https://img.shields.io/badge/Duration-80%20min-lightgrey)

A hands-on, 80-minute session that takes you from "I can already program" to writing, compiling, and running real C++ — and steers you clear of the traps that catch newcomers to the language.

---

## Is this for you?

This Primer is for you if you already understand the *ideas* of programming — variables, conditionals, loops, functions — but are new to **C++** (maybe you're coming from Python, or you're just starting Programming Workshop).

It is **not** a learn-to-program-from-scratch session, and it is **not** the deep dive on pointers, memory, or classes — those each get their own session later. The goal here is to get the language under your fingers.

## What you'll be able to do

By the end of the session you'll be able to:

- Compile and run a C++ program from the command line, and read a compiler error.
- Recognize the standard shape of a C++ program (`#include`, `main`, `return`).
- Use C++'s core types — and explain the integer-division trap that bites everyone.
- Read input and write output with `cin` and `cout`.
- Translate the control flow and functions you already know into correct C++.
- Name the most common "coming-from-another-language" gotchas.

## Getting the files

You don't need to know Git to use this. Either:

- **Clone it** (if you know Git):
  ```
  git clone <repo-url>
  cd cpp-primer
  ```
- **Or download it**: click the green **Code** button above → **Download ZIP**, then unzip.

Then compile and run any file (the lab machines run Linux with `g++`):

```
g++ snippets/hello.cpp -o hello
./hello
```

If your environment isn't cooperating, don't fight it during the session — flag it, and we'll point you to a browser-based compiler so you can keep up while we sort out setup separately.

## How the session runs

We work in a simple loop: **predict → run → discover → consolidate.** For each new idea you'll see a small snippet, guess what it does *before* running it, run it, and then we name the rule together. You'll be typing far more than you'll be watching — bring a laptop or grab a lab machine.

## What's in this repo

```
cpp-primer/
├── snippets/          # the examples we walk through together (full, working code)
│   ├── hello.cpp
│   ├── division.cpp
│   └── average.cpp
├── exercises/         # your turn — starter code + a way to check yourself
│   ├── 01-classify/
│   │   ├── starter.cpp
│   │   └── expected-output.txt
│   ├── 02-even-counter/
│   │   ├── starter.cpp
│   │   └── expected-output.txt
│   └── README.md      # the exercise prompts
├── cheatsheet.md      # the C++ gotchas you'll want to keep
└── docs/
    └── cpp-primer-handout.pdf   # the polished, printable version
```

## Working the exercises

Each exercise gives you a **prompt** and a **starter file** with the skeleton filled in. Your job is to make it work.

To check yourself, every exercise ships with an `expected-output.txt`. Run your program with the sample input, compare your output to the expected output, and you'll know whether you've got it:

```
g++ exercises/01-classify/starter.cpp -o classify
./classify
```

You'll notice there are **no finished solutions in this repo** — and that's on purpose. Writing the code yourself is the part that actually teaches you; reading a finished answer mostly teaches you to recognize one. The expected output is there so you're never working blind, and if you get genuinely stuck, that's exactly what the Primer sessions and **Study Hall** are for. Bring your attempt and we'll work through it with you.

## The polished handout

Prefer something you can print or read away from a screen? The branded version of this Primer — outcomes, exercises, and the gotcha cheat sheet — lives at [`docs/cpp-primer-handout.pdf`](docs/cpp-primer-handout.pdf).

## Where to get help

- **Study Hall** — drop in and work, with someone on hand when you're stuck.
- **Primers & Workshops** — sessions like this one across the courses we support.
- **Tipsheets** — quick references on our nool repository.

## License

Released under the [MIT License](LICENSE). Copyright holder to be confirmed (Student Learning / Ontario Tech University) pending IP sign-off.

---

Maintained by Student Learning, Ontario Tech University.
