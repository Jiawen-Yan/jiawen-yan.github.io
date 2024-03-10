---
layout: archive
title: ""
permalink: /datasets/
author_profile: true
---

**1. Textual Circuitousness**\
*- Guest, Nicholas M. and Yan, Jiawen, 2023, Using Indirect Disclosure to Hide Bad News, [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4098951)*

<p style='text-align: justify;'>Textual circuitousness reflects the indirectness of information is presented in a document. To compute textual circuitousness of each document, we employ the following four step procedure: 1) pre-process document, 2) split document into chunks, 3) represent each chunk in the high-dimensional space, and 4) calculate textual circuitousness, which is the ratio between the total distance it takes going from the first chunk to the last chunk and the distance of the shortest possible path going over all chunks once. This dataset is in Stata format and has two variables: 1) FILENAME, and 2) CIRCUITOUS. FILENAME records the filename in the EDGAR, and CIRCUITOUS records the computed circuitousness. See Guest and Yan (2023) for more technical details on computing progression complexity. </p>

![Textual Circuitousness](https://jiawen-yan.github.io/images/cir.png)

**Download Links**: [[10-K Circuitousness]](https://jiawen-yan.github.io/files/datasets/circuitousness.zip)

