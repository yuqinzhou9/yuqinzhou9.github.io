---
layout: page
title: Language Modeling Using Tensor Trains
description: "[6 Dec 2022] Tensor networks (TNs) are a powerful modeling framework developed for complex quantum systems, and have been recently applied within machine learning.  We propose a novel Tensor Train Language Model, as a first attempt to apply tensor networks on realworld language modeling tasks."

img: assets/pdf/TTLM.pdf
importance: 1
category: Research
---

#### Background

Tensor networks have previously been shown to have potential in language modeling in theory but lack practical evidence support. We propose a novel Tensor Train Language Model (TTLM) based on Tensor-Train decomposition. To show the usefulness of TTLM, we perform a principled experimental evaluation on real-world language modeling tasks, showing that our proposed variants, TTLM-Large and TTLM-Tiny, can be more effective than Vanilla RNNs with low-scale of hidden sizes. Also, we demonstrate the relationship between TTLM and Second-order Recurrent Neural Networks (RNNs), Recurrent Arithmetic Circuits, and Multi-
plicative Integration RNNs in the sense that the architectures of all of these are, essentially, special cases of that of TTLM.


The [report]({{ site.url }}/assets/pdf/language_modeling_using_tensor.pdf) and <a href="https://github.com/tensortrainlm/tensortrainlm">code</a>  for this paper are available.


<!-- <a href="{{ '/assets/pdf/language_modeling_using_tensor.pdf' | prepend: site.baseurl | prepend: site.url }}">report</a> -->
