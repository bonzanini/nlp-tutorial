title: "Fast Python? Don't Bother!"
subtitle:
speaker: russel-winder
---
Python is a programming language that executes slowly. People doing data analysis and other calculations generally require high performance computation. Python people wanting performance computation are generally told, "use Cython", "use NumPy (and SciPy, Pandas, etc.)", "use Numba". Why are they not told "use D", "use Chapel", or even "use C++14"? Chapel in particular is a modern, designed for high performance, parallel computations programming language. Using a multi-language approach is a far better approach to high performance computations. This talk will present data to back up this claim.