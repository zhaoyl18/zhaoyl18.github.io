---
title: "Blessing of Class Diversity in Pre-training"
collection: publications
permalink: /publication/paper-number-2
excerpt: ''
venue: 'preprint'
---
This paper presents a new statistical analysis aiming to explain the recent superior achievements of the pre-training techniques in natural language processing (NLP).
We prove that when the classes of the pre-training task (e.g., different words in masked language model task) are sufficiently diverse, in the sense that the least singular value of the last linear layer in pre-training is large, then pre-training can significantly improve the sample efficiency of downstream tasks.
Inspired by our theory, we propose a new regularization technique that targets the multi-class pre-training: a \emph{diversity regularizer only to the last linear layer} in the pre-training phase.
Our empirical results show that this technique consistently boosts the performance of the pre-trained BERT model on different downstream tasks.
