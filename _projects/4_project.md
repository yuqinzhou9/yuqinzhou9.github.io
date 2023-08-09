---
layout: page
title: Towards Language Modeling Using Tensor Trains
description: "Tensor networks are a powerful modeling framework developed for complex quantum systems.  We propose a novel Tensor Train Language Model, as an illustration of how tensor networks can be applied to real-world language modeling datasets. The paper is under review in ICML"

img: assets/img/TTLM.png
importance: 2
category: Research
---

#### Abstract

Tensor networks have previously shown great potential in language modeling in theory but lack practical implementations in real natural language tasks. To make it practical, we propose a novel tensor network language model based on the simplest tensor network (i.e., tensor trains), called ‘Tensor Train Language Model’ (TTLM). TTLM represents sentences in an exponential space constructed by the tensor product of words, but in practice alternatively, computes the probabilities of sentences in a low-dimensional fashion. Ex- perimental evaluations on real language modeling tasks show that the proposed variants of TTLM (i.e., TTLM-Large and TTLM-Tiny) outperform the vanilla Recurrent Neural Networks (RNNs) with low-scale of hidden units. Interestingly, we demonstrate that the architectures of Second-order RNNs, Recurrent Arithmetic Circuits, and Multiplicative Integration RNNs are, essentially, special cases of that of TTLM


The [preprint]({{ site.url }}/assets/pdf/Towards_Language_Modeling_Using_Tensor_Trains.pdf) and <a href="https://github.com/tensortrainlm/tensortrainlm">code</a>  for this paper are available.


<!-- <a href="{{ '/assets/pdf/language_modeling_using_tensor.pdf' | prepend: site.baseurl | prepend: site.url }}">report</a> -->
