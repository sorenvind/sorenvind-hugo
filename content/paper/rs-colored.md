+++
arxiv = ""
date = "2014-07-01"
description = ""
tags = ["paper", "research"]
title = "Colored Range Searching in Linear Space"
weight = ""

[[authors]]
  name = "Roberto Grossi"
  website = "http://www.di.unipi.it/~grossi/"

[conference]
  link = "http://link.springer.com/chapter/10.1007/978-3-319-08404-6_20"
  name = "SWAT 2014"

+++

In *colored range searching*, we are given a set of $n$ colored points in $d \geq 2$ dimensions to store, and want to support orthogonal range queries taking colors into account. In the *colored range counting* problem, a query must report the number of distinct colors found in the query range, while an answer to the *colored range reporting* problem must report the distinct colors in the query range.  

We give the first linear space data structure for both problems in two dimensions ($d=2$) with $o(n)$ worst case query time. We also give the first data structure obtaining almost-linear space usage and $o(n)$ worst case query time for points in $d > 2$ dimensions. Finally, we present the first dynamic solution to both counting and reporting with $o(n)$ query time for $d \geq 2$ and $d \geq 3$ dimensions, respectively.