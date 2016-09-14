title: 'An introduction to property-based testing'
subtitle:
speaker: alex-chan
---
Testing is a cornerstone of modern software development.  It provides us with a safety net against bugs and regressions – without testing, it would be impossible to write large-scale applications.

The traditional approach to testing relies on hard-coded examples: fire some specific inputs into a function, and compare the result to predetermined, expected output.  This means somebody has to think of examples to test, but humans are notoriously bad at coming up with random data.  So why not let the computer do it for us?

In this talk, you'll learn about property-based testing.  You tell the computer what sort of test data to use, and let it fill in the blanks.  This allows the computer to try many, many more examples than you could write by hand.  It's a great way to find bugs in your software – before they reach your users.

We'll see this style of testing through the lens of Hypothesis, a property-based testing library with Hypothesis.  I'll show you how this style of testing works, some features of Hypothesis, and some testing patterns that let you apply this in your own code.

Pushing this a little further, I'll introduce the idea of stateful testing.  You don't even need to write a test: you just tell Hypothesis how to use your program, and it goes off and tries to break it in interesting ways.