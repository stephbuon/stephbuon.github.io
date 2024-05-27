---
layout: post
title:  'posextractr: A Software Package in R'
description: An R software package providing functions for extracting grammatical subject-verb-object (SVO) and subject-verb-adjective complement/ adjective modifier (SVA) triples from text. This linguistically improved algorithm has significantly higher precision and recall measures than existing methods. 
date:   2020-11-10 15:01:35 +0300
image:  '/images/posextractr.png'
tags:   [R, NLP]
---
posextractr is a software package for extracting grammatical triples. 

See [Syntactic Dependency Parsing for the Extraction of Grammatical Triples](https://stephbuon.github.io/syntactic-dependency-relationships-and-the-extraction-of-grammatical-triples) for descriptions on how extracted triples have been used in research and why triples analysis might open dimensions of analysis for your own area of study! 

posextact has been designed to meet the increasing need for high-accuracy triples outputs for the analysis of text. We propose a solution aimed at reducing errors related to: a) ungrammatical extractions; b) double counting; and c) the missed detection of triples.

For usage instructions or to get a copy, see our [repository on GitHub](https://github.com/stephbuon/posextract). Or install from CRAN (COMING SOON)

Note: 

posextractr is an R wrapper for the Python version, posextract. By following R conventions (such as passing and returning data frames), it is the perfect library for analysts who want results with little set up. For the full functionality of posextract, including under-the-hood access to triples objects, consider installing posextract in Python instead.