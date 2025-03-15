---
title: Topology
summary: undergraduate course with focus on point topology
date: 2024-02-21
type: docs
page_type: subpage
math: true
tags:
  - Topology
image:
  caption: 'Möbius strip'
---
According to Bourbaki, in mathematics we study: 

- structures defined on sets,

- maps that preserve structures.

Roughly speaking, a structure is a set endowed with some additional feathers on the set, usually prescribed via subsets (of subsets of ...).

There are many mathematical structures, among which the following three structures are most elementary (called mother structures): 

- algebraic structure 

- topological structure 

- order structure 

(There are also many other structures: metric structure, measure structure, smooth structure, ......) 

Roughly speaking, a topological structure, or a topology for short, defined on a set, is the structure using which one can talk about the conception of neighborhoods of an element. As a result, with topology at hand, one can talk about the conception of continuity for maps defined on such sets.

So topological structures lie in the center of analysis: it is the topology of $\mathbb{R}$ (or $\mathbb{R}^n$) that allows us to talk about the continuity of (multi-variable) functions.

Many conceptions and theorems we learned in mathematical analysis are topological, and one of the main goals of the first half of point-set topology is trying to extend these conceptions and theorems to more general spaces.

**Theorem (The Intermediate Value Theorem)** Let \(f : [a,b] \to \mathbb{R}\) be a continuous function. Then for any value \(y\) between \(f(a)\) and \(f(b)\), there exists \(c \in [a,b]\) s.t. \(f(c)=y\).

Topological property behind the Intermediate Value Theorem: the connectedness of \([a, b]\)

**Theorem (The Generalized Intermediate Value Theorem)** Let \(X , Y\) be topological spaces, and let \(f: X \to Y\) be a continuous map. Then for any connected subset \(A \subset X\) , the image \(f(A)\) is a connected subset in Y.

In mathematical analysis, we learned Theorem (The Extremal Value Theorem) Let \(f:[a, b] \to \mathbb{R}) be a continuous function. Then f attains both a maximal value and a minimal value.

Easy to see

- The theorem fails if you replace \([a, b]\) by \((a, b)\) or \([a,+\infty)\)

- The theorem holds if you replace \([a, b]\) by \([a, b] \cup[c, d])

Topological property behind the Extremal Value Theorem: compactness of \([a, b]\) .

(We will see: compactness is a generalization of finiteness.) We can easily extend the EVT to

Theorem (The Generalized Extremal Value Theorem) Let \(X , Y\) be topological spaces, and let \(f : X \to Y\) be a continuous map. Then for any compact subset \(A \subset X\) , the image \(f(A)\) is a compact subset in Y.

