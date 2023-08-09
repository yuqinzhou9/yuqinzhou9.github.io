---
layout: page
title: "Reinforced Queries using Pre-trained Language Models in Sparse Retrieval"
description: "We address the persistent issue of query-document mismatch in sparse retrieval by leveraging reinforcement learning and a pre-trained model."

img: assets/img/QRPLM.png
importance: 1
category: Research
---

#### Abstract

Despite the success of dense retrieval, sparse retrieval methods still show potential in interpretability and generalizability. However, query-document term mismatch in sparse retrieval persists, rendering it infeasible for many practical applications. To remedy this, we introduce a novel query expansion approach, denoted as QSparse. QSparse generates expanded terms by pre-trained language models trained by reinforcement learning and then uses a sparse retrieval method to retrieve documents. A thorough experimental evaluation on three datasets from disparate domains (SCIFACT, Natural Questions (NQ), and MS-MARCO passage) shows that QSparse enriches the original query and significantly improves sparse re- trieval. Furthermore, QSparse, when combined with dense retrieval, achieves an 8% improvement in NDCG@10 for SCIFACT and a 2% increase in recall for NQ, compared to the original dense retrieval. These results highlight that QSparse leverages the benefits of both sparse retrieval and dense retrieval to address mismatch issues.


The [preprint]({{ site.url }}/assets/pdf/SIGIR2023.pdf) and <a href="https://anonymous.4open.science/r/QSparse/">code</a>  for this paper are available.


<!-- <a href="{{ '/assets/pdf/language_modeling_using_tensor.pdf' | prepend: site.baseurl | prepend: site.url }}">report</a> -->
