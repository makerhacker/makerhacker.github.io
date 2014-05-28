---
layout: post
title: 50 years neural computation in language sciences 1
categories: [paper]
tags: [neural-computation, language-science]
---


50 years after the perceptron, 25 years after PDP: Neural computation in language sciences

**[1] Recurrent temporal networks and language acquisition—from corticostriatal neurophysiology to reservoir computing**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00500/pdf)

Author: Peter F. Dominey

Abstract:

One of the most paradoxical aspects of human language is that it is so unlike any other form of behavior in the animal world, yet at the same time, it has developed in a species that is not far removed from ancestral species that do not possess language. While aspects of non-human primate and avian interaction clearly constitute communication, this communication appears distinct from the rich, combinatorial and abstract quality of human language. So how does the human primate brain allow for language? In an effort to answer this question, a line of research has been developed that attempts to build a language processing capability based in part on the gross neuroanatomy of the corticostriatal system of the human brain. This paper situates this research program in its historical context, that begins with the primate oculomotor system and sensorimotor sequencing, and passes, via recent advances in reservoir computing to provide insight into the open questions, and possible approaches, for future research that attempts to model language processing. One novel and useful idea from this research is that the overlap of cortical projections onto common regions in the striatum allows for adaptive binding of cortical signals from distinct circuits, under the control of dopamine, which has a strong adaptive advantage. A second idea is that recurrent cortical networks with fixed connections can represent arbitrary sequential and temporal structure, which is the basis of the reservoir computing framework. Finally, bringing these notions together, a relatively simple mechanism can be built for learning the grammatical constructions, as the mappings from surface structure of sentences to their meaning. This research suggests that the components of language that link conceptual structure to grammatical structure may be much simpler that has been proposed in other research programs. It also suggests that part of the residual complexity is in the conceptual system itself.

**[2] The stability-plasticity dilemma: investigating the continuum from catastrophic forgetting to age-limited learning effects**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00504/pdf)

Author: Martial Mermillod, Aurélia Bugaiska and Patrick Bonin

Abstract:

The stability-plasticity dilemma is a well-know constraint for artificial and biological neural systems. The basic idea is that learning in a parallel and distributed system requires plasticity for the integration of new knowledge, but also stability in order to prevent the forgetting of previous knowledge. Too much plasticity will result in previously encoded data being constantly forgotten, whereas too much stability will impede the efficient coding of this data at the level of the synapses. However, for the most part, neural computation has addressed the problems related to excessive plasticity or excessive stability as two different fields in the literature.

**[3] Spoken word recognition without a TRACE**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00563/pdf)

Author: Thomas Hannagan, James S. Magnuson and Jonathan Grainger

Abstract:

How do we map the rapid input of spoken language onto phonological and lexical representations over time? Attempts at psychologically-tractable computational models of spoken word recognition tend either to ignore time or to transform the temporal input into a spatial representation. TRACE, a connectionist model with broad and deep coverage of speech perception and spoken word recognition phenomena, takes the latter approach, using exclusively time-specific units at every level of representation. TRACE reduplicates featural, phonemic, and lexical inputs at every time step in a large memory trace, with rich interconnections (excitatory forward and backward connections between levels and inhibitory links within levels). As the length of the memory trace is increased, or as the phoneme and lexical inventory of the model is increased to a realistic size, this reduplication of time- (temporal position) specific units leads to a dramatic proliferation of units and connections, begging the question of whether a more efficient approach is possible. Our starting point is the observation that models of visual object recognition—including visual word recognition—have grappled with the problem of spatial invariance, and arrived at solutions other than a fully-reduplicative strategy like that of TRACE. This inspires a new model of spoken word recognition that combines time-specific phoneme representations similar to those in TRACE with higher-level representations based on string kernels: temporally independent (time invariant) diphone and lexical units. This reduces the number of necessary units and connections by several orders of magnitude relative to TRACE. Critically, we compare the new model to TRACE on a set of key phenomena, demonstrating that the new model inherits much of the behavior of TRACE and that the drastic computational savings do not come at the cost of explanatory power.

**[4] An amodal shared resource model of language-mediated visual attention**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00528/pdf)

Author: Alastair C. Smith, Padraic Monaghan and Falk Huettig

Abstract:

Language-mediated visual attention describes the interaction of two fundamental components of the human cognitive system, language and vision. Within this paper we present an amodal shared resource model of language-mediated visual attention that offers a description of the information and processes involved in this complex multimodal behavior and a potential explanation for how this ability is acquired. We demonstrate that the model is not only sufficient to account for the experimental effects of Visual World Paradigm studies but also that these effects are emergent properties of the architecture of the model itself, rather than requiring separate information processing channels or modular processing systems. The model provides an explicit description of the connection between the modality-specific input from language and vision and the distribution of eye gaze in language-mediated visual attention. The paper concludes by discussing future applications for the model, specifically its potential for investigating the factors driving observed individual differences in language-mediated eye gaze.

**[5] Integrating probabilistic models of perception and interactive neural networks: a historical and tutorial review**

Source: fpsyg-2013 [pdf](http://journal.frontiersin.org/Journal/10.3389/fpsyg.2013.00503/pdf)

Author: James L. McClelland

Abstract:

This article seeks to establish a rapprochement between explicitly Bayesian models of contextual effects in perception and neural network models of such effects, particularly the connectionist interactive activation (IA) model of perception. The article is in part an historical review and in part a tutorial, reviewing the probabilistic Bayesian approach to understanding perception and how it may be shaped by context, and also reviewing ideas about how such probabilistic computations may be carried out in neural networks, focusing on the role of context in interactive neural networks, in which both bottom-up and top-down signals affect the interpretation of sensory inputs. It is pointed out that connectionist units that use the logistic or softmax activation functions can exactly compute Bayesian posterior probabilities when the bias terms and connection weights affecting such units are set to the logarithms of appropriate probabilistic quantities. Bayesian concepts such the prior, likelihood, (joint and marginal) posterior, probability matching and maximizing, and calculating vs. sampling from the posterior are all reviewed and linked to neural network computations. Probabilistic and neural network models are explicitly linked to the concept of a probabilistic generative model that describes the relationship between the underlying target of perception (e.g., the word intended by a speaker or other source of sensory stimuli) and the sensory input that reaches the perceiver for use in inferring the underlying target. It is shown how a new version of the IA model called the multinomial interactive activation (MIA) model can sample correctly from the joint posterior of a proposed generative model for perception of letters in words, indicating that interactive processing is fully consistent with principled probabilistic computation. Ways in which these computations might be realized in real neural systems are also considered.


