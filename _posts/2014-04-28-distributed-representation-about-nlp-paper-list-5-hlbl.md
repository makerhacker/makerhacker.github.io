---
layout: post
title: distributed reprensentation about nlp paper list 5 m&h hlbl
categories: [paper]
tags: [distributed-reprensentation, nlp, language-model, hlbl]
---


**[1] Three New Graphical Models for Statistical Language Modelling**

Source: icml-2007 [pdf](http://www.cs.toronto.edu/~amnih/papers/threenew.pdf)

Author: Andriy Mnih and Geoffrey Hinton 

Abstract:

The supremacy of n-gram models in statistical language modelling has recently been challenged by parametric models that use distributed representations to counteract the difficulties caused by data sparsity. We propose three new probabilistic language models that define the distribution of the next word in a sequence given several preceding words by using distributed representations of those words. We show how real-valued distributed representations for words can be learned at the same time as learning a large set of stochastic binary hidden features that are used to predict the distributed representation of the next word from previous distributed representations. Adding connections from the previous states of the binary hidden features improves performance as does adding direct connections between the real-valued distributed representations. One of our models significantly outperforms the very best n-gram models.

**[2] A Scalable Hierarchical Distributed Language Model**

Source: nips-2008 [pdf](http://www.cs.toronto.edu/~amnih/papers/hlbl_final.pdf)

Author: Andriy Mnih and Geoffrey Hinton 

Abstract:

Neural probabilistic language models (NPLMs) have been shown to be competitive with and occasionally superior to the widely-used n-gram language models. The main drawback of NPLMs is their extremely long training and testing times. Morin and Bengio have proposed a hierarchical language model built around a binary tree of words, which was two orders of magnitude faster than the non-hierarchical model it was based on. However, it performed considerably worse than its non-hierarchical counterpart in spite of using a word tree created using expert knowledge. We introduce a fast hierarchical language model along with a simple feature-based algorithm for automatic construction of word trees from the data. We then show that the resulting models can outperform non-hierarchical neural models as well as the best n-gram models.

**[3] A fast and simple algorithm for training neural probabilistic language models**

Source: icml-2012 [pdf](http://www.cs.toronto.edu/~amnih/papers/ncelm.pdf)

Author: Andriy Mnih and Yee Whye Teh

Abstract:

In spite of their superior performance, neural probabilistic language models (NPLMs) remain far less widely used than n-gram models due to their notoriously long training times, which are measured in weeks even for moderately-sized datasets. Training NPLMs is computationally expensive because they are explicitly normalized, which leads to having to consider all words in the vocabulary when computing the log-likelihood gradients. We propose a fast and simple algorithm for training NPLMs based on noise-contrastive estimation, a newly introduced procedure for estimating unnormalized continuous distributions. We investigate the behaviour of the algorithm on the Penn Treebank corpus and show that it reduces the training times by more than an order of magnitude without affecting the quality of the resulting models. The algorithm is also more embeddingcient and much more stable than importance sampling because it requires far fewer noise samples to perform well. We demonstrate the scalability of the proposed approach by training several neural language models on a 47M-word corpus with a 80K-word vocabulary, obtaining state-of-the-art results on the Microsoft Research Sentence Completion Challenge dataset.

**[4] Learning word embeddings efficiently with noise-contrastive estimation**

Source: nips-2013 [pdf](http://www.cs.toronto.edu/~amnih/papers/wordreps.pdf)

Author: Andriy Mnih and Koray Kavukcuoglu

Abstract:

Continuous-valued word embeddings learned by neural language models have recently been shown to capture semantic and syntactic information about words very well, setting performance records on several word similarity tasks. The best results are obtained by learning high-dimensional embeddings from very large quantities of data, which makes scalability of the training method a critical factor. We propose a simple and scalable new approach to learning word embeddings based on training log-bilinear models with noise-contrastive estimation. Our approach is simpler, faster, and produces better results than the current state-of-the-art method. We achieve results comparable to the best ones reported, which were obtained on a cluster, using four times less data and more than an order of magnitude less computing time. We also investigate several model types and find that the embeddings learned by the simpler models perform at least as well as those learned by the more complex ones.


