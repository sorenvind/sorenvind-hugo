+++
arxiv = ""
date = "2014-12-01"
description = ""
tags = ["paper", "research"]
title = "Output-Sensitive Pattern Extraction in Sequences"
weight = ""

[[authors]]
  name = "Roberto Grossi"
  website = "http://www.di.unipi.it/~grossi/"

[[authors]]
  name = "Giulia Menconi"
  website = "http://giuliamenconi.weebly.com"

[[authors]]
  name = "Nadia Pisanti"
  website = "http://www.di.unipi.it/~pisanti/"

[[authors]]
  name = "Roberto Trani"

[conference]
  link = "http://drops.dagstuhl.de/opus/volltexte/2014/4851/pdf/27.pdf"
  name = "FSTTCS 2014"

+++

Genomic Analysis, Plagiarism Detection, Data Mining, Intrusion Detection, Spam Fighting and Time Series Analysis are just some examples of applications where extraction of recurring patterns in sequences of objects is one of the main computational challenges.

Several notions of patterns exist, and many share the common idea of strictly specifying some parts of the pattern and to *don't care* about the remaining parts. Since the number of patterns can be exponential in the length of the sequences, *pattern extraction* focuses on statistically relevant patterns, where any attempt to further refine or extend them causes a loss of significant information (number of occurrences).

We address the problem of extracting maximal patterns with at most $k$ don't care symbols and at least $q$ occurrences. We give a simple algorithm with the first known output-sensitive bounds for pattern extraction.