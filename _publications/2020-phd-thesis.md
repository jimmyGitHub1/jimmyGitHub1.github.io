---
title: "Reversing an Imperative Concurrent Programming Language (PhD thesis)"
collection: publications
permalink: /publication/2020-phd-thesis
excerpt: '<a href="https://leicester.figshare.com/articles/thesis/Reversing_an_Imperative_Concurrent_Programming_Language/12656219">[Download]</a>'
date: 2020-07-15
venue: 'Leicester Research Archive, PhD Thesis, University of Leicester'
citation: 'J. Hoey. Reversing an Imperative Concurrent Programming Language. PhD Thesis, University of Leicester. 2020.'
---

[Download this paper here](https://leicester.figshare.com/articles/thesis/Reversing_an_Imperative_Concurrent_Programming_Language/12656219/1)

**Abstract:** We introduce an approach to performing reversible executions of programs written in an imperative concurrent programming language. Our language contains assignments, conditional and loop statements, blocks, local variables, potentially recursive procedures and an interleaving concurrent composition operator par. The traditional execution of programs is defined using Structured Operational Semantics. Given an original, irreversible program we automatically generate two modified versions. The first, named the annotated version, performs forward execution and saves any lost information necessary for reversal. We address challenges of reversing a concurrent execution by using identifiers to capture a specific execution order. All information required for reversal is saved via the operational semantics. We define two further semantics. The first defines annotated execution, performing the expected forward execution and saving all reversal information. The second set defines the behaviour of the inverted version of a program. This forward-executing program simulates reversal, using identifiers to determine the (inverted) execution order, and other reversal information to undo each respective forward step. We produce several results. We show that saving information during a forward execution does not change the behaviour of the underlying program, and that executing an inverted version correctly restores the state to as it was prior to the corresponding forward execution. All reversal information is used during an inverse execution meaning our approach is garbage-free. A simulator, named Ripple, implementing our approach is introduced, based on our three semantics. This shows our approach works, and allows both testing and evaluation of the performance, specifically execution time and memory overheads. Our experimental results show that time and memory overheads increase linearly with respect to the size of the data or program. We explore the use of Ripple within reverse debugging, and identify future work, including optimizations and relaxing the inverted order of independent concurrent statements.

[Back to Publications](https://jimmygithub1.github.io/publications/)
