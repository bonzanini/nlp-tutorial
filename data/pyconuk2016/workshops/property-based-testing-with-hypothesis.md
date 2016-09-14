title: Property-based testing with Hypothesis
speaker: david-r-maciver
---
Hypothesis is a library for writing smarter tests.

Instead of hand-writing every example in your tests, you describe what sorts of examples you need and let it fill in the blanks. It uses this to actively go looking for bugs in your code.

It’s proven very effective, and is being used by an ever growing number of open source projects (including pypy, cryptography, and mercurial), but people sometimes struggle to get started.

In this session we’ll help you overcome that by going through a number of illustrative examples that will help you understand this style of testing better. 

Each example will come with a subtly broken implementation of the problem, and some basic tests for it. Attendees will then extend these tests using Hypothesis to try to flush out the broken behaviour. Afterwards we'll discuss the problems, how we tested them, and I'll suggest any useful avenues to explore that I think people missed.

Depending on how people feel and get on, at the end people will either have a bonus example to explore or are welcome to  bring their own code that they'd like to test better.

At the end of this you should feel much more comfortable with the general concepts of property based testing, and be able to use Hypothesis effectively to test your own code.
