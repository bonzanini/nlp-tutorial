title: 'The state of PyPy '
subtitle:
speaker: ronan-lamy
---
PyPy is a fast and highly-compatible alternative implementation of Python. Its just-in-time compiler, backed by a state-of-the art garbage collector, allow it to run pure-Python(2) code on average 7 times faster than CPython 2.7, the reference implementation.

This presentation will give a tour of PyPy's features with special emphasis on recent developments:

* cpyext, PyPy's emulation layer for CPython's C API, has been overhauled in order to soon allow full compatibility with all C extensions.
* Python 3 support is steadily improving with a recent 3.3-compatible release and development being started on a 3.5 version.