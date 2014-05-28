---
layout: post
title: nlp tookits ocr paper 2 frontier
categories: [paper]
tags: [nlp, ocr]
---


**[1] Multi-digit Number Recognition from Street View Imagery using Deep Convolutional Neural Networks**

Source: iclr-2014 [pdf](http://arxiv.org/pdf/1312.6082v4.pdf)

Author: Ian J. Goodfellow, Yaroslav Bulatov, Julian Ibarz, Sacha Arnoud, Vinay Shet

Abstract:

Recognizing arbitrary multi-character text in unconstrained natural photographs is a hard problem. In this paper, we address an equally hard sub-problem in this domain viz. recognizing arbitrary multi-digit numbers from Street View imagery. Traditional approaches to solve this problem typically separate out the localization, segmentation, and recognition steps. In this paper we propose a unified approach that integrates these three steps via the use of a deep convolutional neural network that operates directly on the image pixels. We employ the DistBelief implementation of deep neural networks in order to train large, distributed neural networks on high quality images. We find that the performance of this approach increases with the depth of the convolutional network, with the best performance occurring in the deepest architecture we trained, with eleven hidden layers. We evaluate this approach on the publicly available SVHN dataset and achieve over 96% accuracy in recognizing complete street numbers. We show that on a per-digit recognition task, we improve upon the state-of-the-art, achieving 97.84% accuracy. We also evaluate this approach on an even more challenging dataset generated from Street View imagery containing several tens of millions of street number annotations and achieve over 90% accuracy. To further explore the applicability of the proposed system to broader text recognition tasks, we apply it to synthetic distorted text from reCAPTCHA. reCAPTCHA is one of the most secure reverse turing tests that uses distorted text to distinguish humans from bots. We report a 99.8% accuracy on the hardest category of reCAPTCHA. Our evaluations on both tasks indicate that at specific operating thresholds, the performance of the proposed system is comparable to, and in some cases exceeds, that of human operators. 

**[2] Deep generative learning of location-invariant visual word recognition**

Source: fpsyg-2013 [pdf](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3776941/pdf/fpsyg-04-00635.pdf)

This article is part of the Research Topic, 50 years after the perceptron, 25 years after PDP: Neural computation in language sciences

Author: Maria Grazia Di Bono and Marco Zorzi 

Abstract:

It is widely believed that orthographic processing implies an approximate, flexible coding of letter position, as shown by relative-position and transposition priming effects in visual word recognition. These findings have inspired alternative proposals about the representation of letter position, ranging from noisy coding across the ordinal positions to relative position coding based on open bigrams. This debate can be cast within the broader problem of learning location-invariant representations of written words, that is, a coding scheme abstracting the identity and position of letters (and combinations of letters) from their eye-centered (i.e., retinal) locations. We asked whether location-invariance would emerge from deep unsupervised learning on letter strings and what type of intermediate coding would emerge in the resulting hierarchical generative model. We trained a deep network with three hidden layers on an artificial dataset of letter strings presented at five possible retinal locations. Though word-level information (i.e., word identity) was never provided to the network during training, linear decoding from the activity of the deepest hidden layer yielded near-perfect accuracy in location-invariant word recognition. Conversely, decoding from lower layers yielded a large number of transposition errors. Analyses of emergent internal representations showed that word selectivity and location invariance increased as a function of layer depth. Word-tuning and location-invariance were found at the level of single neurons, but there was no evidence for bigram coding. Finally, the distributed internal representation of words at the deepest layer showed higher similarity to the representation elicited by the two exterior letters than by other combinations of two contiguous letters, in agreement with the hypothesis that word edges have special status. These results reveal that the efficient coding of written words—which was the model's learning objective—is largely based on letter-level information.


