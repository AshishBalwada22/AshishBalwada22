# Ashish Balwada

**C++ · systems internals · low-level design**

I learn C++ by trying to break it. Most of what's here started as a question I couldn't answer
confidently — *why did the vtable dispatch the wrong function?*, *why did this file handle leak?*,
*why does this queue deadlock under load?* — and ended as a runnable file with the answer written
next to the code.

I care about code that compiles, runs, and explains itself.

---

## What I work on

| Area | What's actually in the repos |
|---|---|
| **C++ internals** | vtables and object layout, constructor ordering, padding, copy vs move, RVO, undefined behaviour, iterator invalidation |
| **Low-level design** | SOLID, creational / structural / behavioural patterns, bad-vs-good refactors of real LLD problems |
| **Concurrency** | `std::thread`, mutex and lock guards, condition variables, `async` / `future` / `promise`, atomics, race and deadlock demos, a thread-safe queue |
| **Algorithms** | graph and DP question banks, Codeforces contest logs, a daily LeetCode habit filed by month |
| **Digital design** | Verilog, from primitives up to a small crash course |
| **Python / ML** | TensorFlow CNNs (MNIST, CIFAR-10), NLP on 20 Newsgroups, Naive Bayes implemented from scratch |

---

## Featured work

### [System-Design](https://github.com/AshishBalwada22/System-Design) — low-level design, in C++
The repo I'd point you to first. Around 30 examples across the four pillars:
- **SOLID** — one file per principle, each with the violation and the fix
- **Design patterns** — factory, abstract factory, builder, singleton · adapter, decorator · strategy, observer, command, template method, most with a UML diagram beside the code
- **Concurrency** — 14 programs, from bare `std::thread` and `lock_guard` up to a `thread_safe_queue` built on `condition_variable`
- **LLD problems** — a parking lot walked through a 10-step design framework, and a Google-Docs exercise written twice, `bad_design.cpp` → `good_design.cpp`

### [Prep](https://github.com/AshishBalwada22/Prep) — C++ interview internals, with output prediction
Twelve topic files where the point isn't the syntax, it's the trap: constructor and destructor ordering with padding, copy vs assignment vs move, `vptr`/`vtable` dispatch, RAII and file-handle safety, iterator invalidation, and undefined behaviour that compiles cleanly and then lies to you. Ends in a 1,100-line bank of "what does this print?" questions.

### [DLC](https://github.com/AshishBalwada22/DLC) — daily LeetCode, filed by month
43 solutions across September and October 2025 plus weekly contests, including the design-an-object problems — movie rental, food rating, spreadsheet, task manager — that LeetCode marks medium and interviewers treat as low-level design.

### [DSA-Questions](https://github.com/AshishBalwada22/DSA-Questions) — contest and concept bank
Graphs (DFS/BFS, DSU, topological sort, round-trip detection), STL technique, number theory and combinatorics, grouped by the idea each problem teaches rather than by problem number.

### [VLSI-Design](https://github.com/AshishBalwada22/VLSI-Design) — Verilog crash course
A 520-line annotated walk through Verilog: modules, `always` blocks, timing, and the mental shift from sequential software to hardware that evaluates in parallel.

---

## Toolbox

**Languages** — C++ (C++11 through C++17), Python, Verilog, SQL

**C++ standard library** — STL containers and algorithms, `<thread>`, `<mutex>`, `<atomic>`, `<future>`, smart pointers

**Python** — NumPy, pandas, scikit-learn, TensorFlow / Keras, Matplotlib

**Concepts** — OOP and SOLID, design patterns, data structures and algorithms, concurrency, database consistency and indexing

**Tooling** — Git, g++, gdb, Linux, Jupyter

---

## Currently

Going deeper on low-level design and C++ internals, and keeping the daily-solve habit alive.

If you want to talk through any of the repos above, open an issue or a discussion on one of them — that's the fastest way to reach me.
