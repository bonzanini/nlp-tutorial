title: 'recipy: completely effortless provenance for Python'
subtitle:
speaker: robin-wilson
---
Imagine the situation: You’ve written some wonderful Python code which produces a beautiful output: a graph, some wonderful data, a lovely musical composition, or whatever. You save that output, naturally enough, as awesome_output.png. You run the code a couple of times, each time making minor modifications. You come back to it the next week/month/year. Do you know how you created that output? What input data? What version of your code? If you’re anything like me then the answer will often, frustratingly, be “no”.

This talk will introduce ReciPy, a Python module that will save you from this situation! With the addition of a single line of code to the top of your Python files, ReciPy will log each run of your code to a database, keeping track of all of your input files, output files and the code that was used - as well as a lot of other useful information. You can then query this easily and find out exactly how that output was created.

ReciPy was originally developed at the Collaborations Workshop 2015 Hack Day, run by the Software Sustainability Institute - a UK-based institute focused on improving the way that computational science is carried out. ReciPy won the Hack Day competition, and has been developed further to make it fully useable, even by novice programmers - and even by those outside of computational science.

ReciPy is built of three separate components: a Python module that hooks into the Python import system so that it can ‘monkey patch’ input/output functions to write to a log before actually doing the input/output, a database stored in MongoDB and a range of interfaces to allow you to find out exactly how you did produce that output.

This talk will be suitable for programmers at all levels: you will hear how to install and use ReciPy and how it will help you (novice), how it hooks into Python (intermediate/advanced) and how you can help with further development (intermediate/advanced)