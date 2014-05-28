---
layout: post
title: nlp tookits ocr paper 1 tesseract
categories: [paper]
tags: [nlp, ocr, tesseract]
---


**[1] An Overview of the Tesseract OCR Engine**

Source: icdar-2007 [pdf](http://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/33418.pdf)

Author: Ray Smith

Abstract:

The Tesseract OCR engine, as was the HP Research Prototype in the UNLV Fourth Annual Test of OCR Accuracy[1], is described in a comprehensive overview. Emphasis is placed on aspects that are novel or at least unusual in an OCR engine, including in particular the line finding, features/classification methods, and the adaptive classifier. 

**[2] Hybrid Page Layout Analysis via Tab-Stop Detection**

Source: icdar-2009 [pdf](http://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/35094.pdf)

Author: Ray Smith

Abstract:

A new hybrid page layout analysis algorithm is proposed, which uses bottom-up methods to form an initial data-type hypothesis and locate the tab-stops that were used when the page was formatted. The detected tab-stops are used to deduce the column layout of the page. The column layout is then applied in a top-down manner to impose structure and reading-order on the detected regions. The complete C++ source code implementation is available as part of the Tesseract open source OCR engine at http://code.google.com/p/tesseract-ocr. 

**[3] Combined Orientation and Script Detection using the Tesseract OCR Engine**

Source: icdar_mocr-2009 [pdf](http://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/35506.pdf)

Author: Ranjith Unnikrishnan, Ray Smith

Abstract:

This paper proposes a simple but effective algorithm to estimate the script and dominant page orientation of the text contained in an image. A candidate set of shape classes for each script is generated using synthetically rendered text and used to train a fast shape classifier. At run time, the classifier is applied independently to connected components in the image for each possible orientation of the component, and the accumulated confidence scores are used to determine the best estimate of page orientation and script. Results demonstrate the effectiveness of the approach on a dataset of 1846 documents containing a diverse set of images in 14 scripts and any of four possible page orientations. 

**[4] Adapting the Tesseract Open Source OCR Engine for Multilingual OCR**

Source: icdar_mocr-2009 [pdf](http://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/35248.pdf)

Author: Ray Smith, Daria Antonova, Dar-Shyang Lee

Abstract:

We describe efforts to adapt the Tesseract open source OCR engine for multiple scripts and languages. Effort has been concentrated on enabling generic multi-lingual operation such that negligible customization is required for a new language beyond providing a corpus of text. Although change was required to various modules, including physical layout analysis, and linguistic post-processing, no change was required to the character classifier beyond changing a few limits. The Tesseract classifier has adapted easily to Simplified Chinese. Test results on English, a mixture of European languages, and Russian, taken from a random sample of books, show a reasonably consistent word error rate between 3.72% and 5.78%, and Simplified Chinese has a character error rate of only 3.77%. 

**[5] Table Detection in Heterogeneous Documents**

Source: iapr_das-2010 [pdf]()

Author: Faisal Shafait, Ray Smith

Abstract:

Detecting tables in document images is important since not only do tables contain important information, but also most of the layout analysis methods fail in the presence of tables in the document image. Existing approaches for table de- tection mainly focus on detecting tables in single columns of text and do not work reliably on documents with varying layouts. This paper presents a practical algorithm for table detection that works with a high accuracy on documents with varying layouts (company reports, newspaper articles, magazine pages, . . . ). An open source implementation of the algorithm is provided as part of the Tesseract OCR engine. Evaluation of the algorithm on document images from pub- licly available UNLV dataset shows competitive performance in comparison to the table detection module of a commercial OCR system. 

**[6] Limits on the Application of Frequency-based Language Models to OCR**

Source: icdar-2011 [pdf](http://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/36984.pdf)

Author: Ray Smith

Abstract:

Although large language models are used in speech recognition and machine translation applications, OCR systems are “far behind” in their use of language models. The reason for this is not the laggardness of the OCR community, but the fact that, at high accuracies, a frequency-based language model can do more damage than good, unless carefully applied. This paper presents an analysis of this discrepancy with the help of the Google Books n-gram Corpus, and concludes that noisy-channel models that closely model the underlying classifier and segmentation errors are required. 

**[7] Improving Book OCR by Adaptive Language and Image Models**

Source: iapr_das-2012 [pdf](http://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/37481.pdf)

Author: Dar-Shyang Lee, Ray Smith

Abstract:

In order to cope with the vast diversity of book content and typefaces, it is important for OCR systems to leverage the strong consistency within a book but adapt to variations across books. In this work, we describe a system that combines two parallel correction paths using document-specific image and language models. Each model adapts to shapes and vocabularies within a book to identify inconsistencies as correction hypotheses, but relies on the other for effective cross-validation. Using the open source Tesseract engine as baseline, results on a large dataset of scanned books demonstrate that word error rates can be reduced by 25% using this approach. 


