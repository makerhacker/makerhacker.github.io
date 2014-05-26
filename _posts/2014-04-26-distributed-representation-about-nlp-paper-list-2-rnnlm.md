---
layout: post
title: distributed reprensentation about nlp paper list 2 rnnlm
categories: [paper]
tags: [distributed-reprensentation, nlp, language-model]
---


## recurrent neural network based language model

**[1] Statistical Language Models based on Neural Networks**

Source: phd-2012 [pdf](http://www.fit.vutbr.cz/~imikolov/rnnlm/thesis.pdf)

Author: Tomas Mikolov

Abstract:

Statistical language models are crucial part of many successful applications, such as automatic speech recognition and statistical machine translation (for example well-known Google Translate). Traditional techniques for estimating these models are based on N-gram counts. Despite known weaknesses of N-grams and huge efforts of research communities across many fields (speech recognition, machine translation, neuroscience, artificial intelligence, natural language processing, data compression, psychology etc.), N-grams remained basically the state-of-the-art. The goal of this thesis is to present various architectures of language models that are based on artificial neural networks. Although these models are computationally more expensive than N-gram models, with the presented techniques it is possible to apply them to state-of-the-art systems efficiently. Achieved reductions of word error rate of speech recognition systems are up to 20%, against state-of-the-art N-gram model. The presented recurrent neural network based model achieves the best published performance on well-known Penn Treebank setup.

**[2] Recurrent neural network based language model**

Source: interspeech-2010 [pdf](http://www.fit.vutbr.cz/research/groups/speech/publi/2010/mikolov_interspeech2010_IS100722.pdf)

Author: Mikolov Tomáš, Karafiát Martin, Burget Lukáš, Černocký Jan, Khudanpur Sanjeev

Abstract:

A new recurrent neural network based language model (RNNLM) with applications to speech recognition is presented. Results indicate that it is possible to obtain around 50% reduction of perplexity by using mixture of several RNN LMs, compared to a state of the art backoff language model. Speech recognition experiments show around 18% reduction of word error rate on the Wall Street Journal task when comparing models trained on the same amount of data, and around 5% on the much harder NIST RT05 task, even when the backoff model is trained on much more data than the RNN LM. We provide ample empirical evidence to suggest that connectionist language models are superior to standard n-gram techniques, except their high computational (training) complexity.

**[3] Extensions of Recurrent Neural Network Language Model**

Source: icassp-2011 [pdf](http://www.fit.vutbr.cz/research/groups/speech/publi/2011/mikolov_icassp2011_5528.pdf)

Author: Mikolov Tomáš, Kombrink Stefan, Burget Lukáš, Černocký Jan, Khudanpur Sanjeev

Abstract:

We present several modifications of the original recurrent neural network language model (RNN LM). While this model has been shown to significantly outperform many competitive language modeling techniques in terms of accuracy, the remaining problem is the computational complexity. In this work, we show approaches that lead to more than 15 times speedup for both training and testing phases. Next, we show importance of using a backpropagation through time algorithm. An empirical comparison with feedforward networks is also provided. In the end, we discuss possibilities how to reduce the amount of parameters in the model. The resulting RNN model can thus be smaller, faster both during training and testing, and more accurate than the basic one.

**[4] Empirical Evaluation and Combination of Advanced Language Modeling Techniques**

Source: interspeech-2011 [pdf](http://www.fit.vutbr.cz/~imikolov/rnnlm/is2011_emp.pdf)

Author: Mikolov Tomáš, Deoras Anoop, Kombrink Stefan, Burget Lukáš, Černocký Jan

Abstract:

We present results obtained with several advanced language modeling techniques, including class based model, cache model, maximum entropy model, structured language model, random forest language model and several types of neural network based language models. We show results obtained after combining all these models by using linear interpolation. We conclude that for both small and moderately sized tasks, we obtain new state of the art results with combination of models, that is significantly better than performance of any individual model. Obtained perplexity reductions against Good-Turing trigram baseline are over 50% and against modified Kneser-Ney smoothed 5-gram over 40%.

**[5] RNNLM - Recurrent Neural Network Language Modeling Toolkit**

Source: asru-2011 [pdf](http://www.fit.vutbr.cz/~imikolov/rnnlm/rnnlm-demo.pdf)

Author: Mikolov Tomáš, Kombrink Stefan, Deoras Anoop, Burget Lukáš, Černocký Jan

Abstract:

We present freely available open-source toolkit for training recurrent neural network based language models. It can be easily used to improve existing speech recognition and machine translation systems. Also, it can be used as a baseline for future research of advanced language modeling techniques. In the paper, we discuss optimal parameter selection and different modes of functionality. The toolkit, example scripts and basic setups are freely available at http://rnnlm.sourceforge.net/.

**[6] Strategies for Training Large Scale Neural Network Language Models**

Source: asru-2011 [pdf](http://www.fit.vutbr.cz/~imikolov/rnnlm/asru_large_v4.pdf)

Author: Mikolov Tomáš, Deoras Anoop, Povey Daniel, Burget Lukáš, Černocký Jan

Abstract:

We describe how to effectively train neural network based language models on large data sets. Fast convergence during training and better overall performance is observed when the training data are sorted by their relevance. We introduce hash-based implementation of a maximum entropy model, that can be trained as a part of the neural network model. This leads to significant reduction of computational complexity. We achieved around 10% relative reduction of word error rate on English Broadcast News speech recognition task, against large 4-gram model trained on 400M tokens.


