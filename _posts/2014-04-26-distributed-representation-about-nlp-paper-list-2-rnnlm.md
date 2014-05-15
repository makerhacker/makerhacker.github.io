---
layout: post
title: distributed-reprensentation-about-nlp-paper-list-2 rnnlm
categories: [paper]
tags: [distributed-reprensentation, nlp, language-model]
---


recurrent neural network based language model
=============================================

[1] phd-2012: Statistical Language Models based on Neural Networks [pdf](http://www.fit.vutbr.cz/~imikolov/rnnlm/thesis.pdf)

Author: Tomas Mikolov

Abstract:
Statistical language models are crucial part of many successful applications, such as automatic speech recognition and statistical machine translation (for example well-known Google Translate). Traditional techniques for estimating these models are based on N-gram counts. Despite known weaknesses of N-grams and huge efforts of research communities across many fields (speech recognition, machine translation, neuroscience, artificial intelligence, natural language processing, data compression, psychology etc.), N-grams remained basically the state-of-the-art. The goal of this thesis is to present various architectures of language models that are based on artificial neural networks. Although these models are computationally more expensive than N-gram models, with the presented techniques it is possible to apply them to state-of-the-art systems efficiently. Achieved reductions of word error rate of speech recognition systems are up to 20%, against state-of-the-art N-gram model. The presented recurrent neural network based model achieves the best published performance on well-known Penn Treebank setup.

[2] interspeech-2010: Recurrent neural network based language model [pdf](http://www.fit.vutbr.cz/research/groups/speech/publi/2010/mikolov_interspeech2010_IS100722.pdf)

Author: Mikolov Tomáš, Karafiát Martin, Burget Lukáš, Černocký Jan, Khudanpur Sanjeev

Abstract:
A new recurrent neural network based language model (RNNLM) with applications to speech recognition is presented. Results indicate that it is possible to obtain around 50% reduction of perplexity by using mixture of several RNN LMs, compared to a state of the art backoff language model. Speech recognition experiments show around 18% reduction of word error rate on the Wall Street Journal task when comparing models trained on the same amount of data, and around 5% on the much harder NIST RT05 task, even when the backoff model is trained on much more data than the RNN LM. We provide ample empirical evidence to suggest that connectionist language models are superior to standard n-gram techniques, except their high computational (training) complexity.


