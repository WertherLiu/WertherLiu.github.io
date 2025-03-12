---
title: Topology
summary: undergraduate course with focus on point topology
date: 2024-02-21
type: docs
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

**Theorem (The Intermediate Value Theorem)** Let \(f : [a,b] $\to$ $\mathbb{R}$\) be a continuous function. Then for any value \(y\) between \(f(a)\) and \(f(b)\), there exists \(c $\in$ [a,b]\) s.t. \(f(c)=y\).

Topological property behind the Intermediate Value Theorem: the connectedness of \([a, b]\)

**Theorem (The Generalized Intermediate Value Theorem)** Let X , Y be topological spaces, and let \(f: X $\to$ Y\) be a continuous map. Then for any connected subset \(A $\subset$ X\) , the image \(f(A)\) is a connected subset in Y.

In mathematical analysis, we learned Theorem (The Extremal Value Theorem) Let \(f:[a, b] $\to$ $\mathbb{R}$) be a continuous function. Then f attains both a maximal value and a minimal value.

Easy to see

- The theorem fails if you replace \([a, b]\) by \((a, b)\) or \([a,$+\infty$)\)

- The theorem holds if you replace \([a, b]\) by \([a, b] $\cup[c, d]$)

Topological property behind the Extremal Value Theorem: compactness of \([a, b]\) .

(We will see: compactness is a generalization of finiteness.) We can easily extend the EVT to

Theorem (The Generalized Extremal Value Theorem) Let X , Y be topological spaces, and let f : XY be a continuous map. Then for any compact subset \(A \subset X\) , the image \(f(A)\) is a compact subset in Y

## Math

Hugo Blox Builder supports a Markdown extension for $\LaTeX$ math. You can enable this feature by toggling the `math` option in your `config/_default/params.yaml` file.

To render _inline_ or _block_ math, wrap your LaTeX math with `{{</* math */>}}$...${{</* /math */>}}` or `{{</* math */>}}$$...$${{</* /math */>}}`, respectively.

{{% callout note %}}
We wrap the LaTeX math in the Hugo Blox _math_ shortcode to prevent Hugo rendering our math as Markdown.
{{% /callout %}}

Example **math block**:

```latex
{{</* math */>}}
$$
\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}
$$
{{</* /math */>}}
```

renders as

{{< math >}}
$$\gamma_{n} = \frac{ \left | \left (\mathbf x_{n} - \mathbf x_{n-1} \right )^T \left [\nabla F (\mathbf x_{n}) - \nabla F (\mathbf x_{n-1}) \right ] \right |}{\left \|\nabla F(\mathbf{x}_{n}) - \nabla F(\mathbf{x}_{n-1}) \right \|^2}$$
{{< /math >}}

Example **inline math** `{{</* math */>}}$\nabla F(\mathbf{x}_{n})${{</* /math */>}}` renders as {{< math >}}$\nabla F(\mathbf{x}_{n})${{< /math >}}.

Example **multi-line math** using the math linebreak (`\\`):

```latex
{{</* math */>}}
$$f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}$$
{{</* /math */>}}
```

renders as

{{< math >}}

$$
f(k;p_{0}^{*}) = \begin{cases}p_{0}^{*} & \text{if }k=1, \\
1-p_{0}^{*} & \text{if }k=0.\end{cases}
$$

{{< /math >}}

