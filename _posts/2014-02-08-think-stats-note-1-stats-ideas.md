---
layout: post
title: think-stats-note-1 statistical thinking
categories: [book]
tags: [probability, statistics, python]
---

Why we learn probability and statistics with a computational approach using python?
-----------------------------------------------------------------------------------
Here are some answers from the author:

* Students write programs as a way of developing and testing their understanding.
For example, they write functions to compute a least squares fit, residuals,
and the coefficient of determination. Writing and testing this code requires them 
to understand the concepts and implicitly corrects misunderstandings.

* Students run experiments to test statistical behavior. For example, they explore 
the Central Limit Theorem (CLT) by generating samples from several distributions. 
When they see that the sum of values from a Pareto distribution doesn’t converge to
normal, they remember the assumptions the CLT is based on.

* Some ideas that are hard to grasp mathematically are easy to understand by simulation. 
For example, we approximate p-values by running Monte Carlo simulations, which reinforces 
the meaning of thep-value.

* Using discrete distributions and computation makes it possible to present topics 
like Bayesian estimation that are not usually covered in an introductory class. 
For example, one exercise asks students to compute the posterior distribution 
for the “German tank problem,” which is difficult analytically but surprisingly 
easy computationally.

* Because students work in a general-purpose programming language (Python), 
they are able to import data from almost any source. They are not limited to data 
that has been cleaned and formatted for a particular statistics tool.

Three topics in this book
-------------------------

* Probability is the study of random events. Most people have an intuitive understanding 
of degrees of probability, which is why you can use words like “probably” and “unlikely” 
without special training, but we will talk about how to make quantitative claims about 
those degrees.

* Statistics is the discipline of using data samples to support claims about populations. 
Most statistical analysis is based on probability, which is why these pieces are usually 
presented together.

* Computation is a tool that is well-suited to quantitative analysis, and computers are 
commonly used to process statistics. Also, computational experiments are useful for 
exploring concepts in probability and statistics.

One Question: Do first babies arrive late?
------------------------------------------

Some answers like these:

- “My two friends that have given birth recently to their first babies, BOTH went almost 
2 weeks overdue before going into labour or being induced.”

- “My first one came 2 weeks late and now I think the second one is going to come out 
two weeks early!!”

- “I don’t think that can be true because my sister was my mother’s first and she was early, 
as with many of my cousins.”

Reports like these are called anecdotal evidence because they are based on data that is 
unpublished and usually personal. 

- Small number of observations: If the gestation period is longer for first babies, 
the difference is probably small compared to the natural variation. In that case, 
we might have to compare a large number of pregnancies to be sure that a difference exists.

- Selection bias: People who join a discussion of this question might be interested because 
their first babies were late. In that case the process of selecting data would bias the results.

- Confirmation bias: People who believe the claim might be more likely to contribute examples 
that confirm it. People who doubt the claim are more likely to cite counterexamples.

- Inaccuracy: Anecdotes are often personal stories, and often misremembered, misrepresented, 
repeated inaccurately, etc.

How about a statistical approach?
---------------------------------

- Data collection: We will use data from a large national survey that was designed explicitly 
with the goal of generating statistically valid inferences about the U.S. population.

- Descriptive statistics: We will generate statistics that summarize the data concisely, 
and evaluate different ways to visualize data.

- Exploratory data analysis: We will look for patterns, differences, and other features that 
address the questions we are interested in. At the same time we will check for inconsistencies 
and identify limitations.

- Hypothesis testing: Where we see apparent effects, like a difference between two groups, 
we will evaluate whether the effect is real, or whether it might have happened by chance.

- Estimation: We will use data from a sample to estimate characteristics of the general population.

The NSFG dataset
----------------

Since 1973 the U.S. Centers for Disease Control and Prevention (CDC) have conducted the 
National Survey of Family Growth (NSFG), which is intended to gather “information on 
family life, marriage and divorce, pregnancy, infertility, use of contraception, and 
men’s and women’s health. The survey results are used ... to plan health services and 
health education programs, and to do statistical studies of families, fertility, and health.”

The NSFG is a cross-sectional study, which means that it captures a snapshot of a group 
at a point in time. 
The most common alternative is a longitudinal study, which observes a group repeatedly 
over a period of time.

The NSFG is not representative; instead it is deliberately oversampled. The designers 
of the study recruited three groups—Hispanics, AfricanAmericans and teenagers—at rates 
higher than their representation in the U.S. population. The reason for oversampling 
is to make sure that the number of respondents in each of these groups is large enough 
to draw valid statistical inferences.

Now it is time to program!
-------------------------

Compute the average pregnancy length (in weeks) for first babies and others. Is there 
a difference between the groups? How big is it?

Significance Level
------------------

The running result: first babies are born about 13 hours later, on average.
A difference like that is called an apparent effect; that is, there might be something 
going on, but we are not yet sure.

• If the two groups have different means, what about other summary statistics, like median 
and variance? Can we be more precise about how the groups differ?

• Is it possible that the difference we saw could occur by chance, even if the groups we 
compared were actually the same? If so, we would conclude that the effect was not 
statistically significant.

• Is it possible that the apparent effect is due to selection bias or some other error 
in the experimental setup? If so, then we might conclude that the effect is an artifact; 
that is, something we created (by accident) rather than found.

Go forward!
-----------

