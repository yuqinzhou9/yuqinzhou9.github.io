---
layout: page
title: "QRPLM: Query Reformulation using Pre-trained Language Model with Reinforcement Learning"
description: "We address the persistent issue of query-document mismatch in sparse retrieval by leveraging reinforcement learning and a pre-trained model. The paper is under review in SIGIR."

img: assets/img/QRPLM.png
importance: 1
category: Research
---

#### Abstract

In spite of substantial efforts, the issue of mismatching between query and document in sparse retrieval persists. To address this problem, we propose a novel query formulation named QRPLM based on Reinforcement Learning from Human Feedback (RLHF). Specifically, the pre-trained language model is employed as a query reformulator under the framework of reinforcement learning, where the reward is based on the evaluation metric. Our evaluation of QRPLM on two widely-used information retrieval datasets, namely SCIFACT and Neural Question (NQ), demonstrates that QRPLM can enrich the original query and significantly outperform the sparse retrieval. Furthermore, the fusion of QRPLM and dense retrieval results in an improvement of 8% on SCIFACT in terms of NDCG@10 and 2% on NQ in terms of recall, as compared to the original dense retrieval. Notably, our evaluation results demonstrate that QRPLM enables the utilization of the advantages of both sparse retrieval and dense retrieval in addressing the mismatch issue. Our solution and code are publicly available on GitHub


The [under review]({{ site.url }}/assets/pdf/SIGIR2023.pdf) and <a href="https://anonymous.4open.science/r/trl-C1A1/">code</a>  for this paper are available.


<!-- <a href="{{ '/assets/pdf/language_modeling_using_tensor.pdf' | prepend: site.baseurl | prepend: site.url }}">report</a> -->
