---
permalink: /training-modules/software-engineering.html
layout: default
title: Software Engineering for Scientific Computing
---

# Software Engineering for Scientific Computing training module

The goal of this course is to teach basic tools and principles of writing good
code, in the context of scientific computing. Specific topics include an
overview of relevant compiled and interpreted languages, build tools and source
managers, design patterns, design of interfaces, debugging and testing,
profiling and improving performance, portability, and an introduction to
parallel computing in both shared memory and distributed memory environments.
The focus is on writing code that is easy to maintain and share with others. You
will develop these skills through a series of programming assignments and a
group project.

[Source repository](https://github.com/henryiii/se-for-sci) •
[WebAssembly version](https://henryiii.github.io/se-for-sci/live) •
[Binder version](https://mybinder.org/v2/gh/henryiii/se-for-sci/main?urlpath=lab)

Note the WebAssembly version does not have a shell, and `time.sleep` doesn't
work (the web is async).

- [Course syllabus](/assets/pdf/software-engineering/software-engineering-intro.pdf)

## Topics:

### Week 1: Intro

- [Introductions and motivation](https://henryiii.github.io/se-for-sci/content/week1/intro.html)
- [Unix setup and tools](https://henryiii.github.io/se-for-sci/content/week1/setup.html)
- [Version control overview](https://henryiii.github.io/se-for-sci/content/week1/vcs.html)
- [Version control quick intro](https://henryiii.github.io/se-for-sci/content/week1/vcs.html#version-control-quick-intro)
- [Programming basics](https://henryiii.github.io/se-for-sci/content/week1/programming_basics.html)
- [Programming/style general practices](https://henryiii.github.io/se-for-sci/content/week1/practices.html)
- [Code cleanup example](https://henryiii.github.io/se-for-sci/content/week1/cleanup_bessel.html)

### Week 2: Testing

- [Intro to testing](https://henryiii.github.io/se-for-sci/content/week2/testing.html)
- [Intro to pytest](https://henryiii.github.io/se-for-sci/content/week2/pytest.html)
- [Test Driven Development (TDD)](https://henryiii.github.io/se-for-sci/content/week2/tdd.html)
- [Logging & Debugging](https://henryiii.github.io/se-for-sci/content/week2/debugging.html)

### Week 3: Object Oriented design

- [Intro to Object Oriented Programming (OOP)](https://henryiii.github.io/se-for-sci/content/week3/introoo.html)
- [Object Oriented Design](https://henryiii.github.io/se-for-sci/content/week3/oodesign.html)

### Week 4: Design Patterns

- [Design patterns](https://henryiii.github.io/se-for-sci/content/week4/designpatt.html)
- [Functional programming](https://henryiii.github.io/se-for-sci/content/week4/functional.html)

### Week 5: Static Typing

- [Static Typing](https://henryiii.github.io/se-for-sci/content/week5/typing.html)

### Week 6: Version Control

- [Version Control](https://henryiii.github.io/se-for-sci/content/week6/git.html)

### Week 7: Packaging and Quality Control

- [Packaging and quality control](https://henryiii.github.io/se-for-sci/content/week7/packaging.html)
- [Using packages](https://henryiii.github.io/se-for-sci/content/week7/using_packages.html)
- [Making a Package](https://henryiii.github.io/se-for-sci/content/week7/making_a_package.html)
- [Pre-commit](https://henryiii.github.io/se-for-sci/content/week7/precommit.html)
- [Task runners](https://henryiii.github.io/se-for-sci/content/week7/task_runners.html)

### Week 8: Continuous Integration

- [Continuous Integration](https://henryiii.github.io/se-for-sci/content/week8/ci.html)
- [Continuous Deployment](https://henryiii.github.io/se-for-sci/content/week8/cd.html)
- [Generating documentation](https://henryiii.github.io/se-for-sci/content/week8/docs.html)

### Week 9: Intro to Compilation

- [Using Compiled Languages](https://henryiii.github.io/se-for-sci/content/week9/Compiled_Languages.html)

### Week 10: Profiling

- [Debugging](https://henryiii.github.io/se-for-sci/content/week10/debugging.html)
- [Profiling](https://henryiii.github.io/se-for-sci/content/week10/profiling.html)

### Week 11: Parallel Computing

- [Introduction to parallel computing](https://henryiii.github.io/se-for-sci/content/week11/intro.html)
- [Programming with OpenMP](https://henryiii.github.io/se-for-sci/content/week11/openmp.html)
- [Programming with MPI](https://henryiii.github.io/se-for-sci/content/week11/mpi.html)

### Week 12: Mixing Languages

- [Shared object files](https://henryiii.github.io/se-for-sci/content/week12/01-shared-objects/01-shared-objects.html)
- [CFFI](https://henryiii.github.io/se-for-sci/content/week12/01-shared-objects/01-shared-objects.html#cffi)
- [Mix and match with Numba and more](https://henryiii.github.io/se-for-sci/content/week12/01-shared-objects/01-shared-objects.html#mix-and-match-with-numba-and-more)
- [CPython](https://henryiii.github.io/se-for-sci/content/week12/02-cpython/02-cpython.html)
- [Exercise](https://henryiii.github.io/se-for-sci/content/week12/02-cpython/02-cpython.html#exercise)
- [More binding situations](https://henryiii.github.io/se-for-sci/content/week12/03-pybind/03a-pybind.html)
- [Binding detailed example: Minuit2](https://henryiii.github.io/se-for-sci/content/week12/03-pybind/03b-pybind.html)
- [Step 1: Get source](https://henryiii.github.io/se-for-sci/content/week12/03-pybind/03b-pybind.html#step-1-get-source)
- [Step 2: Plan interface](https://henryiii.github.io/se-for-sci/content/week12/03-pybind/03b-pybind.html#step-2-plan-interface)
- [Usage](https://henryiii.github.io/se-for-sci/content/week12/03-pybind/03b-pybind.html#usage)
- [Done](https://henryiii.github.io/se-for-sci/content/week12/03-pybind/03b-pybind.html#done)

### Bonus: Exotic topics

- [WebAssembly](https://henryiii.github.io/se-for-sci/content/week13/webassembly.html)
- [Useful shell tools and tricks](https://henryiii.github.io/se-for-sci/content/week13/shell.html)

Taught by [Henry Schreiner](/collaborators/henryiii) (Princeton University) in Fall, 2022.
