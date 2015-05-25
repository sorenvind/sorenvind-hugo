+++
arxiv = "http://arxiv.org/abs/1305.2777"
date = "2013-08-01"
description = ""
tags = ["paper", "research"]
title = "Fingerprints in Compressed Strings"
weight = ""

[[authors]]
  name = "Philip Bille"
  website = "http://www2.compute.dtu.dk/~phbi/"

[[authors]]
  name = "Patrick Hagge Cording"
  website = "http://www2.imm.dtu.dk/~phaco/"

[[authors]]
  name = "Inge Li Gørtz"
  website = "http://www2.imm.dtu.dk/~ilg/"

[[authors]]
  name = "Benjamin Sach"
  website = "http://www.cs.bris.ac.uk/~sach/"
  
[[authors]]
  name = "Hjalte Wedel Vildhøj"
  website = "http://hwv.dk/"

[conference]
  link = ""
  name = "WADS 2013"

+++

The Karp-Rabin fingerprint of a string is a type of hash value that due to its strong properties has been used in many string algorithms. In this paper we show how to construct a data structure for a string $S$ of size $N$ compressed by a context-free grammar of size $n$ that answers fingerprint queries. That is, given indices $i$ and $j$, the answer to a query is the fingerprint of the substring $S[i,j]$. We present the first $O(n)$ space data structures that answer fingerprint queries without decompressing any characters. For Straight Line Programs (SLP) we get $O(\log N)$ query time, and for Linear SLPs (an SLP derivative that captures LZ78 compression and its variations) we get $O(\log \log N)$ query time. Hence, our data structures has the same time and space complexity as for random access in SLPs. We utilize the fingerprint data structures to solve the longest common extension problem in query time $O(\log N\log \ell)$ and $O(\log \ell \log\log \ell + \log\log N)$ for SLPs and Linear SLPs, respectively. Here, $\ell$ denotes the length of the LCE.