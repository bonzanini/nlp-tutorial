title: 'The Art of Doing Nothing – Using profiling to speed up your code'
subtitle:
speaker: charlie-clark
---
We're lucky with Python that we can concentrate on getting the job done and often don't have to worry about how fast our code runs. Those of us without computer science degrees really know how to appreciate this. And 9 times out of 10 you probably don't need to worry at all about the speed: if the program takes 10 minutes to run but saves you hours of work then it's a job well done. But then there is that 10th time…

Based on work done over the last couple of years with openpyxl I will show some tips and tricks as to how you can approach improving performance without having to become a mathematical genius or computer whizz. There is lots of good advice about performance around but it has to make sense within the context of your application: does it matter that Python loops are considered slow? What kind of a role does memory play?

The talk will cover using tests and profiling to identify the areas that you need to work on, stop you breaking stuff irreparably, and what things you might want to research or ask about. I do promise you: the art of performance really is the art of doing nothing!