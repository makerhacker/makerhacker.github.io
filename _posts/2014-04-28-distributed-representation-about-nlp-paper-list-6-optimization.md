---
layout: post
title: distributed reprensentation about nlp paper list 6 optimization
categories: [paper]
tags: [distributed-reprensentation, nlp, language-model]
---


**[1] Word representations: A simple and general method for semi-supervised learning**

Source: acl-2010 [pdf](http://www.iro.umontreal.ca/~lisa/pointeurs/turian-wordrepresentations-acl10.pdf)

Author: Joseph Turian, Lev Ratinov, Yoshua Bengio

Abstract:

If we take an existing supervised NLP system, a simple and general way to improve accuracy is to use unsupervised word representations as extra word features. We evaluate Brown clusters, Collobert and Weston (2008) embeddings, and HLBL (Mnih & Hinton, 2009) embeddings of words on both NER and chunking. We use near state-of-the-art supervised baselines, and find that each of the three word representations improves the accuracy of these baselines. We find further improvements by combining different word representations. You can download our word features, for off-the-shelf use in existing NLP systems, as well as our code, here: http://metaoptimize.com/projects/wordreprs/

**[2] Improving Word Representations via Global Context and Multiple Word Prototypes**

Source: acl-2012 [pdf](http://nlp.stanford.edu/pubs/HuangACL12.pdf)

Author: Eric H. Huang, Richard Socher, Christopher D. Manning, Andrew Y. Ng

Abstract:

Unsupervised word representations are very useful in NLP tasks both as inputs to learning algorithms and as extra word features in NLP systems. However, most of these models are built with only local context and one representation per word. This is problematic because words are often polysemous and global context can also provide useful information for learning word meanings. We present a new neural network architecture which 1) learns word embeddings that better capture the semantics of words by incorporating both local and global document context, and 2) accounts for homonymy and polysemy by learning multiple embeddings per word. We introduce a new dataset with human judgments on pairs of words in sentential context, and evaluate our model on it, showing that our model outperforms competitive baselines and other neural 
language models.

