---
layout: post
title: think-stats-note-2 descriptive statistics
categories: [book]
tags: [probability, statistics, python]
---

mean and average
================

μ = 1/n ∑x[i]

- The “mean” of a sample is the summary statistic computed with the
previous formula.

- An “average” is one of many summary statistics you might choose to
describe the typical value or the central tendency of a sample.

mean and variance
=================

σ^2 = 1/n ∑(x[i] − μ)^2

- The mean is intended to describe the central tendency.

- The variance is intended to describe the spread.

probability distribution and representation
===========================================

matplotlib.pyplot plotting

histogram
=========

{% highlight c %}
hist = {}
for x in t:
	hist[x] = hist.get(x, 0) + 1
{% endhighlight %}

probability mass function
=========================

{% highlight c %}
n = float(len(t))
pmf = {}
for x, freq in hist.items():
	pmf[x] = freq / n
{% endhighlight %}

outliers
========

trim the data by discarding some fraction of the highest and lowest values

relative risk
=============

conditional probability
=======================

reporting results
=================

The answer might depend on who is asking the question. 


