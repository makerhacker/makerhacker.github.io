---
layout: post
title: search-engine-1 nutch-solr-start
categories: [search]
tags: [nutch, solr]
---

Automated QA agent is the first project, idea from siri, kinect and watson. She can hear my questions then say the answer in natual language, and see all the real-word things then understand them.

The key tech is natual language processing, computer vision and search engine. Search engine is the first area in my career, so we start from here.

Firstly, we must get some blogs, news, books, products and many other datas.

Nutch is a good start.

Nutch common config:

http://wiki.apache.org/nutch/NutchTutorial

http://wiki.apache.org/nutch/FrontPage

1. start shell

config JAVA_HOME (NUTCH_JAVA_HOME)

2. test crawling

bin/nutch crawl urls_file -dir crawl_dir -depth 3 -topN 5

Solr common config:

http://lucene.apache.org/solr/tutorial.html

http://wiki.apache.org/solr/

1. test shell

example java -jar start.jar

2. web page

http://localhost:8983/solr/


