title: 'Easy solutions to hard problems'
subtitle:
speaker: david-r-maciver
---
A lot of interesting problems are computationally hard: Travelling salesmen, colouring graphs, packing knapsack. These are all what's called "NP-hard", which most people usually hear as meaning "intractable".

But actually we have good tools for solving specific NP hard problems, and most NP hard problems can be reduced to them. When you do this it turns out that although there are pathological cases, most individual instances of NP hard problems you're likely to encounter are quite tractable in practice.

Amongst these  tools are Mixed Integer Linear Programming solvers. There are high quality open source implementations (and amazing proprietary ones), and they're actually much easier to use than you might expect.

We'll start with a quick overview of the idea of NP-hardness and introduce some common NP-hard problems. We'll then see how to transform these problems into forms we can feed to a solver. We'll finish with some practical examples of how this sort of thing can be useful in day to day problems.