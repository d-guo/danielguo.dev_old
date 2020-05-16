---
layout: post
title: A List of Counterexamples from Analysis [updated 04/03/2020]
excerpt: Some cool counterexamples I've encountered in Analysis or Topology [ongoing].
modified: 2020-04-03
categories: [mathematics]
comments: true
pinned: true
---

Some cool counterexamples I've encountered in Analysis or Topology. Most of these are fairly standard but still fun nonetheless :). I plan to eventually add a section clarifying the notation I use, but mostly it should be standard or obvious from context.

1.1 **A closed ball which is not the closure of the corresponding open ball** <br/>
Let $X$ be any metric space with 2 or more elements equipped with the discrete metric, and consider the closed and open balls of radius $1$ around any element of $X$. Let $x \in X$ and see $B_{o}(x; 1) = \\{x\\}$ and $B_{c}(x; 1) = X$. Then see that $\overline{B_{o}(x; 1)} = \overline{\\{x\\}} = \\{x\\}$, so we have
\\[
    \overline{B_{o}(x; 1)} = \\{x\\} \neq X = B_{c}(x; 1),
\\]
since $X$ has at least two elements.

2.1 **A sequence of continuous functions which converge pointwise to a discontinuous function**<br/>
Consider the sequence of functions $(f_{n})_ {n \in \mathbb{Z}^{+}}$ where $f_{n}: [0, 1] \to \mathbb{R}$ is defined by $f_{n}(x) = x^{n}$, and denote its pointwise limit $f$. For fixed $x \in [0, 1)$, $x^{n}$ converges to $0$ and for $x = 1$, $x^{n} = 1$ converges to $1$. Thus,
\\[
    f(x) =
    \begin{cases}
        0 & \text{if $x \in [0, 1)$} \\\
        1 & \text{if $x = 1$}
    \end{cases},
\\]
which of course is discontinuous.

2.2 **A sequence of continuous functions which converge pointwise but not uniformly to a continuous function**

![img1]({{ site.url }}/assets/graph1.png)