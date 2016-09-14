title: 'Simulating a CPU with Python or: surprising programs you might have thought were better written in C'
subtitle:
speaker: sarah-mount
---
Can you imagine writing a complete functional simulator for a CPU architecture in Python? This talk describes the Revelation simulator for the Adapteva Epiphany architecture. The simulator is written in RPython,  the restricted Python that underlies the PyPy interpreter, and uses Pydgin, a framework for writing CPU simulators . Revelation is simple to understand (because Python) but also fast (thanks to the automatically generated just-in-time interpreter provided by the RPython toolchain). By the end of this talk you will be convinced that functional simulators for complex CPU architectures can actually be pretty simple to implement.