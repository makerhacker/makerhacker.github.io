---
layout: post
title: distributed reprensentation about nlp paper list 4 senna
categories: [paper]
tags: [distributed-reprensentation, nlp, language-model, senna]
---


**[1] A Unified Architecture for Natural Language Processing: Deep Neural Networks with Multitask Learning**

Source: icml-2008 [pdf](http://ronan.collobert.com/pub/matos/2008_nlp_icml.pdf)

Author: Ronan Collobert, Jason Weston

Abstract:

We describe a single convolutional neural network architecture that, given a sentence, outputs a host of language processing predictions: part-of-speech tags, chunks, named entity tags, semantic roles, semantically similar words and the likelihood that the sentence makes sense (grammatically and semantically) using a language model. The entire network is trained jointly on all these tasks using weight-sharing, an instance of multitask learning. All the tasks use labeled data except the language model which is learnt from unlabeled text and represents a novel form of semi-supervised learning for the shared tasks. We show how both multitask learning and semi-supervised learning improve the generalization of the shared tasks, resulting in state-of-the-art performance.

**[2] Deep Learning for Ecient Discriminative Parsing**

Source: aistats-2011 [pdf](http://ronan.collobert.com/pub/matos/2011_parsing_aistats.pdf)

Author: Ronan Collobert

Abstract:

We propose a new fast purely discriminative algorithm for natural language parsing, based on a deep recurrent convolutional graph transformer network (GTN). Assuming a decomposition of a parse tree into a stack of levels, the network predicts a level of the tree taking into account predictions of previous levels. Using only few basic text features which leverage word representations from Collobert and Weston (2008), we show similar performance (in F1 score) to existing pure discriminative parsers and existing benchmark parsers (like Collins parser, probabilistic context-free grammars based), with a huge speed advantage.

**[3] Natural Language Processing (almost) from Scratch**

Source: jmlr-2011 [pdf](http://ronan.collobert.com/pub/matos/2011_nlp_jmlr.pdf)

Author: R. Collobert, J. Weston, L. Bottou, M. Karlen, K. Kavukcuoglu and P. Kuksa

Abstract:

We propose a unified neural network architecture and learning algorithm that can be applied to various natural language processing tasks including: part-of-speech tagging, chunking, named entity recognition, and semantic role labeling. This versatility is achieved by trying to avoid task-specific engineering and therefore disregarding a lot of prior knowledge. Instead of exploiting man-made input features carefully optimized for each task, our system learns internal representations on the basis of vast amounts of mostly unlabeled training data. This work is then used as a basis for building a freely available tagging system with good performance and minimal computational requirements.



