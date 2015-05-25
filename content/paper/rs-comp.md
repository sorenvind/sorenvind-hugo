+++
arxiv = ""
date = "2015-02-01"
description = ""
tags = ["paper", "research"]
title = "Compressed Data Structures for Range Searching"
weight = ""

[[authors]]
  name = "Philip Bille"
  website = "http://www2.compute.dtu.dk/~phbi/"

[[authors]]
  name = "Inge Li Gørtz"
  website = "http://www2.imm.dtu.dk/~ilg/"

[conference]
  link = "http://link.springer.com/chapter/10.1007/978-3-319-15579-1_45"
  name = "LATA 2015"

+++

We study the orthogonal range searching problem on points that have a significant number of *geometric repetitions*, that is, subsets of points that are identical under translation. Such repetitions occur in scenarios such as image compression, GIS applications and in compactly representing sparse matrices and web graphs. Our contribution is twofold. 

First, we show how to compress geometric repetitions that may appear in standard range searching data structures (such as K-D trees, Quad trees, Range trees, R-trees, Priority R-trees, and K-D-B trees), and how to implement subsequent range queries on the compressed representation with only a constant factor overhead. 

Secondly, we present a compression scheme that efficiently identifies geometric repetitions in point sets, and produces a hierarchical clustering of the point sets, which combined with the first result leads to a compressed representation that supports range searching.