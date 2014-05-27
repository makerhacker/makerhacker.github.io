---
layout: post
title: big data tools paper 2 hadoop
categories: [paper]
tags: [big-data, hadoop]
---


**[1] Improving MapReduce Performance in Heterogeneous Environments**

Source: osdi-2008 [pdf](https://www.usenix.org/legacy/events/osdi08/tech/full_papers/zaharia/zaharia.pdf)

Author: Matei Zaharia, Andy Konwinski, Anthony D. Joseph, Randy Katz and Ion Stoica

Abstract:

MapReduce is emerging as an important programming model for large-scale data-parallel applications such as web indexing, data mining, and scientific simulation. Hadoop is an open-source implementation of MapReduce enjoying wide adoption and is often used for short jobs where low response time is critical. Hadoop’s performance is closely tied to its task scheduler, which implicitly assumes that cluster nodes are homogeneous and tasks make progress linearly,and uses these assumptions to decide when to speculatively re-execute tasks that appear to be stragglers. In practice, the homogeneity assumptions do not always hold. An especially compelling setting where this occurs is a virtualized data center,such as Amazon’s Elastic Compute Cloud (EC2). We show that Hadoop’s scheduler can cause severe performance degradation in heterogeneous environments. We design a new scheduling algorithm, Longest Approximate Time to End (LATE), that is highly robust to heterogeneity. LATE can improve Hadoop response times by a factor of 2 in clusters of 200 virtual machines on EC2.

**[2] SALSA: Analyzing Logs as State Machines**

Source: wasl-2008 [pdf](https://www.usenix.org/legacy/event/wasl08/tech/full_papers/tan/tan.pdf)

Author: Jiaqi Tan, Xinghao Pan, Soila Kavulya, Rajeev Gandhi, Priya Narasimhan

Abstract:

SALSA examines system logs to derive state-machine views of the sytem’s execution, along with control-flow, data-flow models and related statistics. Exploiting SALSA’s derived views and statistics, we can effectively construct higher-level useful analyses. We demonstrate SALSA’s approach by analyzing system logs generated in a Hadoop cluster, and then illustrate SALSA’s value by developing visualization and failure-diagnosis techniques, for three different Hadoop workloads, based on our derived state-machine views and statistics.

**[3] Mochi: Visual Log-Analysis Based Tools for Debugging Hadoop**

Source: hotcloud-2009 [pdf](https://www.usenix.org/legacy/event/hotcloud09/tech/full_papers/tan.pdf)

Author: Jiaqi Tan, Xinghao Pan, Soila Kavulya, Rajeev Gandhi, Priya Narasimhan

Abstract:

Mochi, a new visual, log-analysis based debugging tool correlates Hadoop’s behavior in space, time and volume, and extracts a causal, unified control- and data-flow model of Hadoop across the nodes of a cluster. Mochi’s analysis produces visualizations of Hadoop’s behavior using which users can reason about and debug performance issues. We provide examples of Mochi’s value in revealing a Hadoop job’s structure, in optimizing real-world workloads, and in identifying anomalous Hadoop behavior, on the Yahoo! M45 Hadoop cluster.

**[4] Ganesha: Black-Box Diagnosis for MapReduce Systems**

Source: sigmetrics-2009 [pdf](http://www.sigmetrics.org/conferences/sigmetrics/2009/workshops/papers_hotmetrics/session1_1.pdf)

Author: Xinghao Pan, Jiaqi Tan, Soila Kavulya, Rajeev Gandhi, Priya Narasimhan

Abstract:

Ganesha aims to diagnose faults transparently (in a black-box manner) in MapReduce systems, by analyzing OS-level metrics. Ganesha's approach is based on peer-symmetry under fault-free conditions, and can diagnose faults that manifest asymmetrically at nodes within a MapReduce system. We evaluate Ganesha by diagnosing Hadoop problems for the Gridmix Hadoop benchmark on 10-node and 50-node MapReduce clusters on Amazon's EC2. We also candidly highlight faults that escape Ganesha's diagnosis.


