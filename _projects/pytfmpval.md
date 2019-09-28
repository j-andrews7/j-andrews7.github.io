---
title: "pytfmpval"
excerpt: "A python wrapper around TFM-Pvalue."
header:
  teaser: /assets/images/pytfmpval_unsplash.png
sidebar:
  - title: "Role"
    text: "Creator, Maintainer"
  - title: "Status"
    text: "Stable"
classes: wide
---

[pytfmpval](https://pytfmpval.readthedocs.io/en/latest/) is a python wrapper around [TFMP-value](https://bioinfo.lifl.fr/tfm-pvalue/tfm-pvalue.php), a C++ program that calculates p-values and corresponding score thresholds for transcription factor position weight matrices and position specific scoring matrices. The original program was written by [Hélène Touzet & Jean-Stéphane Varré](https://almob.biomedcentral.com/articles/10.1186/1748-7188-2-15), and while very useful, it is not amenable for high-throughput work or integration with other motif analysis packages. I wrote the python wrapper as a means to determine if non-coding sequence variants in regulatory elements might be breaking or creating transcription factor motifs that impact gene expression. Ultimately, the project I wrote it for was dropped, but it was a good opportunity to learn how to wrap C functions in python.

## Reference
H. Touzet and J.S. Varré. Efficient and accurate P-value computation for Position Weight Matrices.
Algorithms for Molecular Biology 2007, 2:15