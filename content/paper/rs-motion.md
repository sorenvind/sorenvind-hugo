+++
arxiv = ""
date = "2014-12-01"
description = ""
tags = ["paper", "research"]
title = "Indexing Motion Detection Data for Surveillance Video"
weight = ""

[[authors]]
  name = "Philip Bille"
  website = "http://www2.compute.dtu.dk/~phbi/"

[[authors]]
  name = "Inge Li Gørtz"
  website = "http://www2.imm.dtu.dk/~ilg/"

[conference]
  link = ""
  name = "ISM 2014"

+++

We show how to compactly index video data to support fast *motion detection* queries.  A query specifies an area $A$ in the video, a time interval $T$ and two thresholds: a minimum pixel value change $v$ and minimal percentage $p$ of $A$ affected by said change. The answer to a query is the list of timestamps in $T$ where at least $p\%$ of the pixels in $A$ has changed by at least $v$ values.
 
Our results show that by building a small index, we can support queries with a speedup of two or three orders of magnitude compared to motion detection without an index. For high resolution video, the index size is about $20\%$ of the compressed video size.

The [prototype source code and test data set](https://github.com/sorenvind/phd-motiondetectionindex) is available on github.