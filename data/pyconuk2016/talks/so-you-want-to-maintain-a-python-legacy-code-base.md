title: 'So you "want" to maintain a Python legacy code base?'
subtitle:
speaker: cesar-cardenas-desales
---
While many programmers will agree that implementing new Software is the most entertaining part of our jobs, the truth is that the vast majority of developers spend a great amount of time performing maintenance, which in an world that praises innovation "is a dirty job that somebody's gotta do".

In this talk I will describe a series of techniques and Python tools that have proven useful for taking over a legacy code base and getting it move forward, all within a well defined process:

1. Understand. Hold your horses! Don't touch that code yet, even it you really want to. Understand the spirit of your project, its architecture. Ask around, create personas, poll users, document the product.
2. Get yourself a safety net. Create lots of unit tests, pytest or nose are your friends.
3. Enhance. Start with small improvements, check and beautify your code with tools such as flake8, pep8 and pylint, perform code reviews.
