---
layout: post
title: distributed-reprensentation-about-nlp-paper-list-3 word2vec
categories: [paper]
tags: [distributed-reprensentation, nlp, language-model]
---


word2vec
========

[1] naacl-2013:  Linguistic Regularities in Continuous Space Word Representations [pdf](http://research.microsoft.com/pubs/189726/rvecs.pdf)

Author: Tomas Mikolov, Wen-tau Yih, and Geoffrey Zweig

Abstract:
Continuous space language models have recently demonstrated outstanding results across a variety of tasks. In this paper, we examine the vector-space word representations that are implicitly learned by the input-layer weights. We find that these representations are surprisingly good at capturing syntactic and semantic regularities in language, and that each relationship is characterized by a relation-specific vector offset. This allows vector-oriented reasoning based on the offsets between words. For example, the male/female relationship is automatically learned, and with the induced vector representations, “King - Man + Woman” results in a vector very close to “Queen.” We demonstrate that the word vectors capture syntactic regularities by means of syntactic analogy questions (provided with this paper), and are able to correctly answer almost 40% of the questions. We demonstrate that the word vectors capture semantic regularities by using the vector offset method to answer SemEval-2012 Task 2 questions. Remarkably, this method outperforms the best previous systems.

[2] iclr-2013: Efficient Estimation of Word Representations in Vector Space [pdf](http://arxiv.org/pdf/1301.3781.pdf)

Author: Tomas Mikolov, Kai Chen, Greg Corrado, and Jeffrey Dean

Abstract:
We propose two novel model architectures for computing continuous vector representations of words from very large data sets. The quality of these representations is measured in a word similarity task, and the results are compared to the previously best performing techniques based on different types of neural networks. We observe large improvements in accuracy at much lower computational cost, i.e. it takes less than a day to learn high quality word vectors from a 1.6 billion words data set. Furthermore, we show that these vectors provide state-of-the-art performance on our test set for measuring syntactic and semantic word similarities.

[3] nips-2013: Distributed Representations of Words and Phrases and their Compositionality [pdf](http://arxiv.org/pdf/1310.4546.pdf)

Author: Tomas Mikolov, Ilya Sutskever, Kai Chen, Greg Corrado, and Jeffrey Dean

Abstract:
The recently introduced continuous Skip-gram model is an efficient method for learning high-quality distributed vector representations that capture a large number of precise syntactic and semantic word relationships. In this paper we present several extensions that improve both the quality of the vectors and the training speed. By subsampling of the frequent words we obtain significant speedup and also learn more regular word representations. We also describe a simple alternative to the hierarchical softmax called negative sampling. An inherent limitation of word representations is their indifference to word order and their inability to represent idiomatic phrases. For example, the meanings of “Canada” and “Air” cannot be easily combined to obtain “Air Canada”. Motivated by this example, we present a simple method for finding phrases in text, and show that learning good vector representations for millions of phrases is possible.


