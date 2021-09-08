---
layout: post
title:  'Course Materials: Text Mining as Historical Method'
description: An overview of materials designed for an introductory class on applying computation methods for digital history. A link to the full course material is included.
date:   2021-08-10 15:01:35 +0300
image:  '/images/race-over-time-1870_20101024.jpg'
tags:   [Pedagogy, Digital History, Python, JupyterLab]
---
### About this Course

Computer-powered methods are changing the way that we access information about society. New methods help us to detect change over time, to identify influential figures, and to name turning points. What happens when we apply these tools to a million congressional debates or tweets?  

I designed and collaborated on a series of Jupyter Notebooks for Jo Gulid's class, "Text Mining as Historical Method," to explore questions like these. The Notebooks for the class provide an introduction to the cutting-edge methodologies of textual analysis that are transforming the humanities. They are geared towards both computationalists as well as those with a background in the humanities (but not code) and are designed to teach the skills of analyzing texts as data for evidence of change over time. 

This post provides an overview of the material used by "Text Mining as Historical Method." For the full course materials, including the interactive Jupyter Notebooks used by the class, please see the [digital-history](https://github.com/stephbuon/digital-history) repository. 

Becuase this class encourages exploring discourses that have shaped our culture throughout time, students have access to a diverse range of data sets for their own research projects. These data sets include: Reddit posts from the Push Shift API from 2008 to 2015; the 19th-century Hansard Parliamentary debates of Great Britain; the Stanford Congressional Records; the Dallas, Texas and Houston, Texas City Council Minutes; literature from Project Gutenberg; metadata from the NovelTM Datasets for English-Language Fiction, 1700-2009; and corporate reports from EDGAR, the Electronic Data Gathering, Analysis, and Retrieval system. 

The skills practiced in this course begin with basic word counts and visualization techniques and extend to the high-level application of machine learning modules to tell digital history, modules such as spaCy, sci-kit learn, and gensim for word embeddings. By the end of the course students are able to perform comparative analyses and observe how langauge chnages over time. 

### Course Overview

**Week 1** provides an introduction to GitHub and JupyterLab. It also prepares students to work on Southern Methodist University's mainframe computer, M2. Students learn basic `git` commands to clone and pull from the [digital-history](https://github.com/stephbuon/digital-history) repository and how to set up their coding environment on M2 to run Jupter Notebooks. 

**Week 2** covers basic programming concepts in Python such as iteration, indexing elements, data types, and basic data structures. At the end of this week, students are able to perform a basic wordcount of text scraped from the Old Bailey, and are able to visualize their counts with a bar chart. 

**Week 3** introduces basic concepts in textual analytics and natural language processing, concepts such as stemming, lemmatization, regular expressions, n-grams, and bag-of-words analysis. These methods are used to understand the importance of word co-occurance in textual corpora. 

**Week 4** introduces NLTK's wordnet, a lexical database of English nouns, verbs, adjectives, and adverbs. Through wordnet these parts-of-speech are grouped into sets of cognitive synonyms (synsets) and hyponyms

 and are interlinked within a network of conceptual-semantic and lexical relations. Using wordnet, students analyze 




**Week 5** teaches how to work with tabular data and date time types. After an overview of methods to work with dates and time, students render a dot plot that follows the conventions for visualizing time data within digital history scholarship. 

**Week 6** applies the concepts introduced in week 5 to analyze U.S. congressional debates from the 1980's. Using a controlled vocabulary consisting of keywords about crime, students extract, clean, and wrangle the speech of important congressional speakers. The data is then visualized with a line chart to show how the frequency of these speakers' top words change throughout the decade. 

**Week 8**

**Week 9** uses spaCy to answer a guided research question: from a 2008 sample of the Subreddits, "Worldnews," "News," and "Politics," which adjectives modify which verbs in discourses that describe different genders? After mining for gendered nouns and their adjective modifiers, students are able to visualize the different kinds of actions that are associated with male and female nouns and pronouns. 

**Week 10** uses log likelihood to measure "distinctiveness" in a sample data set of quarterly reports on American corporations from EDGAR. Students process the data using tools from the scikit-learn module of statistics and machine learning, focusing on count vectorizorization. Students produce multiple visualizations for comparing and analyzing the distinct words in these reports.

**Week 11** 

**Week 12**