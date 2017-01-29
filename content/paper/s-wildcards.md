+++
arxiv = "http://arxiv.org/abs/1110.5236"
date = "2012-07-01"
description = ""
tags = ["paper", "research"]
title = "String Indexing for Patterns with Wildcards"
weight = ""

[[authors]]
  name = "Philip Bille"
  website = "http://www2.compute.dtu.dk/~phbi/"

[[authors]]
  name = "Inge Li Gørtz"
  website = "http://www2.imm.dtu.dk/~ilg/"

[[authors]]
  name = "Hjalte Wedel Vildhøj"
  website = "http://hwv.dk/"

[conference]
  link = "http://link.springer.com/chapter/10.1007%2F978-3-642-31155-0_25"
  name = "SWAT 2012"

[journal]
  link = "http://link.springer.com/article/10.1007%2Fs00224-013-9498-4"
  name = "Theory of Computing Systems"

+++

We consider the problem of indexing a string $t$ of length $n$ to report the occurrences of a query pattern $p$ containing $m$ characters and $j$ wildcards. Let $occ$ be the number of occurrences of $p$ in $t$, and $\sigma$ the size of the alphabet. We obtain the following results.

* A linear space index with query time $O(m+\sigma^j \log \log n + occ)$.
This significantly improves the previously best known linear space index by Lam et al. [ISAAC 2007], which requires query time $\Theta(jn)$ in the worst case.
* An index with query time $O(m+j+occ)$ using space $O(\sigma^{k^2} n \log^k \log n)$, where $k$ is the maximum number of wildcards allowed in the pattern. This is the first non-trivial bound with this query time.
* A time-space trade-off, generalizing the index by Cole et al. [STOC 2004].

Our results are obtained using a novel combination of well-known and new techniques, which could be of independent interest.
