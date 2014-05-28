---
layout: post
title: 50 years neural computation in language sciences 2
categories: [paper]
tags: [neural-computation, language-science]
---


50 years after the perceptron, 25 years after PDP: Neural computation in language sciences

**[1] Deep generative learning of location-invariant visual word recognition**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00635/pdf)

Author: Maria Grazia Di Bono and Marco Zorzi

Abstract:

It is widely believed that orthographic processing implies an approximate, flexible coding of letter position, as shown by relative-position and transposition priming effects in visual word recognition. These findings have inspired alternative proposals about the representation of letter position, ranging from noisy coding across the ordinal positions to relative position coding based on open bigrams. This debate can be cast within the broader problem of learning location-invariant representations of written words, that is, a coding scheme abstracting the identity and position of letters (and combinations of letters) from their eye-centered (i.e., retinal) locations. We asked whether location-invariance would emerge from deep unsupervised learning on letter strings and what type of intermediate coding would emerge in the resulting hierarchical generative model. We trained a deep network with three hidden layers on an artificial dataset of letter strings presented at five possible retinal locations. Though word-level information (i.e., word identity) was never provided to the network during training, linear decoding from the activity of the deepest hidden layer yielded near-perfect accuracy in location-invariant word recognition. Conversely, decoding from lower layers yielded a large number of transposition errors. Analyses of emergent internal representations showed that word selectivity and location invariance increased as a function of layer depth. Word-tuning and location-invariance were found at the level of single neurons, but there was no evidence for bigram coding. Finally, the distributed internal representation of words at the deepest layer showed higher similarity to the representation elicited by the two exterior letters than by other combinations of two contiguous letters, in agreement with the hypothesis that word edges have special status. These results reveal that the efficient coding of written words—which was the model's learning objective—is largely based on letter-level information.

**[2] A computational model to investigate assumptions in the headturn preference procedure**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00676/pdf)

Author: Christina Bergmann, Louis ten Bosch, Paula Fikkert and Lou Boves

Abstract:

In this paper we use a computational model to investigate four assumptions that are tacitly present in interpreting the results of studies on infants' speech processing abilities using the Headturn Preference Procedure (HPP): (1) behavioral differences originate in different processing; (2) processing involves some form of recognition; (3) words are segmented from connected speech; and (4) differences between infants should not affect overall results. In addition, we investigate the impact of two potentially important aspects in the design and execution of the experiments: (a) the specific voices used in the two parts on HPP experiments (familiarization and test) and (b) the experimenter's criterion for what is a sufficient headturn angle. The model is designed to be maximize cognitive plausibility. It takes real speech as input, and it contains a module that converts the output of internal speech processing and recognition into headturns that can yield real-time listening preference measurements. Internal processing is based on distributed episodic representations in combination with a matching procedure based on the assumptions that complex episodes can be decomposed as positive weighted sums of simpler constituents. Model simulations show that the first assumptions hold under two different definitions of recognition. However, explicit segmentation is not necessary to simulate the behaviors observed in infant studies. Differences in attention span between infants can affect the outcomes of an experiment. The same holds for the experimenter's decision criterion. The speakers used in experiments affect outcomes in complex ways that require further investigation. The paper ends with recommendations for future studies using the HPP.

**[3] Modeling language and cognition with deep unsupervised learning: a tutorial overview**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00515/pdf)

Author: Marco Zorzi, Alberto Testolin and Ivilin P. Stoianov

Abstract:

Deep unsupervised learning in stochastic recurrent neural networks with many layers of hidden units is a recent breakthrough in neural computation research. These networks build a hierarchy of progressively more complex distributed representations of the sensory data by fitting a hierarchical generative model. In this article we discuss the theoretical foundations of this approach and we review key issues related to training, testing and analysis of deep networks for modeling language and cognitive processing. The classic letter and word perception problem of McClelland and Rumelhart (1981) is used as a tutorial example to illustrate how structured and abstract representations may emerge from deep generative learning. We argue that the focus on deep architectures and generative (rather than discriminative) learning represents a crucial step forward for the connectionist modeling enterprise, because it offers a more plausible model of cortical learning as well as a way to bridge the gap between emergentist connectionist models and structured Bayesian models of cognition.

**[4] Experience and generalization in a connectionist model of Mandarin Chinese relative clause processing**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00767/pdf)

Author: Yaling Hsiao and Maryellen C. MacDonald

Abstract:

Sentences containing relative clauses are well known to be difficult to comprehend, and they have long been an arena in which to investigate the role of working memory in language comprehension. However, recent work has suggested that relative clause processing is better described by ambiguity resolution processes than by limits on extrinsic working memory. We investigated these alternative views with a Simple Recurrent Network (SRN) model of relative clause processing in Mandarin Chinese, which has a unique pattern of word order across main and relative clauses and which has yielded mixed results in human comprehension studies. To assess the model's ability to generalize from similar sentence structures, and to observe effects of ambiguity through the sentence, we trained the model on several different sentence types, based on a detailed corpus analysis of Mandarin relative clauses and simple sentences, coded to include patterns of noun animacy in the various structures. The model was evaluated on 16 different relative clause subtypes. Its performance corresponded well to human reading times, including effects previously attributed to working memory overflow. The model's performance across a wide variety of sentence types suggested that the seemingly inconsistent results in some prior empirical studies stemmed from failures to consider the full range of sentence types in empirical studies. Crucially, sentence difficulty for the model was not simply a reflection of sentence frequency in the training set; the model generalized from similar sentences and showed high error rates at points of ambiguity. The results suggest that SRNs are a powerful tool to examine the complicated constraint-satisfaction process of sentence comprehension, and that understanding comprehension of specific structures must include consideration of experiences with other similar structures in the language.

**[5] Context, cortex, and associations: a connectionist developmental approach to verbal analogies**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00857/pdf)

Author: Pavlos Kollias and James L. McClelland

Abstract:

We present a PDP model of binary choice verbal analogy problems (A:B as C:[D1|D2], where D1 and D2 represent choice alternatives). We train a recurrent neural network in item-relation-item triples and use this network to test performance on analogy questions. Without training on analogy problems per se, the model explains the developmental shift from associative to relational responding as an emergent consequence of learning upon the environment's statistics. Such learning allows gradual, item-specific acquisition of relational knowledge to overcome the influence of unbalanced association frequency, accounting for association effects of analogical reasoning seen in cognitive development. The network also captures the overall degradation in performance after anterior temporal damage by deleting a fraction of learned connections, while capturing the return of associative dominance after frontal damage by treating frontal structures as necessary for maintaining activation of A and B while seeking a relation between C and D. While our theory is still far from being complete it provides a unified explanation of findings that need to be considered together in any integrated account of analogical reasoning.


