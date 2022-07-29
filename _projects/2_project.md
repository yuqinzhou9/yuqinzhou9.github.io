---
layout: page
title: Features, Architecture, Combine Them Together
description: "[12 June 2022] Word embeddings are powerful  even when not accompanied by a neural network model. " In this course project, we 
img: assets/img/tweets_length_per_user.png
importance: 2
category: Courses
---

#### Background

This work is the course project of the <a href="https://github.com/yuqinzhou9/course-language_processing_2/blob/main/LP2_course_description.pdf">Lanuage Processing 2 (LP2)</a> at the University of Copenhagen. The project topic is a shared task at <a href="https://pan.webis.de/clef22/pan22-web/author-profiling.html">CLEF 2022</a> about classifying authors as ironic or not depending on their number of tweets with ironic content.  The code and <a href="https://github.com/yuqinzhou9/course-language_processing_2/blob/main/LangII_report.pdf">report</a>  for this paper are available and its abstract is shown below:

This research uses <a href="https://pan.webis.de/clef22/pan22-web/author-profiling.html">the CLEF 2022 dataset</a> to profile ironic and stereotype spreaders on Twitter, representing their tweets at three levels: naive features, sparse vectors, and embeddings. We employ three classic machine learning classifiers (logistic regression, support vector machine, and random forest), as well as a new architecture dubbed the voting model, to combine the strength of each feature. The findings highlight the merit of embeddings, which include subword-level information in particular. Furthermore, de- pending on the classifier’s mechanism, the quality of the features will affect the classifiers to varying degrees.