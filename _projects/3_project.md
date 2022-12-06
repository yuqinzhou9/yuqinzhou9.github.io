---
layout: page
title: 
description: "[6 Dec 2022] Tensor networks (TNs) are a powerful modeling framework developed for complex quantum systems, and have been recently applied within machine learning.  We propose a novel Tensor Train Language Model, as a first attempt to apply tensor networks on realworld language modeling tasks."

img: assets/pdf/TTLM.pdf
importance: 1
category: Research
---

#### Background

This work is the course project of the <a href="https://github.com/yuqinzhou9/course-language_processing_2/blob/main/LP2_course_description.pdf">Lanuage Processing 2 (LP2)</a> at the University of Copenhagen. The project topic is a shared task at <a href="https://pan.webis.de/clef22/pan22-web/author-profiling.html">CLEF 2022</a> about classifying authors as ironic or not depending on their number of tweets with ironic content.  The code and <a href="https://github.com/yuqinzhou9/course-language_processing_2/blob/main/LangII_report.pdf">report</a>  for this paper are available and its abstract is shown below:

This research uses <a href="https://pan.webis.de/clef22/pan22-web/author-profiling.html">the CLEF 2022 dataset</a> to profile ironic and stereotype spreaders on Twitter, representing their tweets at three levels: naive features, sparse vectors, and embeddings. We employ three classic machine learning classifiers (logistic regression, support vector machine, and random forest), as well as a new architecture dubbed the voting model, to combine the strength of each feature. The findings highlight the merit of embeddings, which include subword-level information in particular. Furthermore, depending on the classifier’s mechanism, the quality of the features will affect the classifiers to varying degrees.