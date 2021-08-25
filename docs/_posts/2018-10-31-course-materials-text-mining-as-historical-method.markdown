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

I designed and collaborated on a series of Jupyter Notebooks for Jo Gulid's class, "Text Mining as Historical Method," to explore questions like these. The Notebooks for this class provide an introduction to the cutting-edge methodologies of textual analysis that are transforming the humanities. They are geared towards both computationalists as well as those with a background in the humanities (but not code) and are designed to teach the skills of analyzing texts as data for evidence of change over time. 

This post provides an overview of the material used by "Text Mining as Historical Method." For full course materials, including interactive Jupyter Notebooks used by the class, see the [digital-history](https://github.com/stephbuon/digital-history) repository. (ENTER DEM LAB REPO STUFF)

(the data sets used: Electronic Data Gathering, Analysis, and Retrieval system, EDGAR. )

### Course Overview

**Week 1** provides an introduction to various tools used in this course and across computational fields including GitHub and JupyterLab. It also prepares students to work on Southern Methodist University's mainframe computer, M2. Students learn basic `git` commands to clone and pull from the [digital-history](https://github.com/stephbuon/digital-history) repository, and set up their coding environment on M2 to run the JupterNotebooks for class. 

**Week 2** covers basic programming concepts in Python such as for loops and indexing elements. At the end of the Notebook, students are equipt to perform a basic wordcount of text from the Old Bailey, and visualize their counts with a bar chart. 

**Week 3** introduces basic concepts in textual analytics and natural language processing such as stemming, lemmatization, regular expressions, and n-grams for bag-of-words analysis. Students process text by lemmatizing or stemmming it, and then divide text into tokens or bigrams. With bigrams, students use regular experssions to match with n-grams that contain a word of interest. This activity is useful for understanding word co-occurance in text.

**Week 4** 


**Week 5**

**Week 6**

**Week 8**

**Week 9** puts spaCy to work to answer a larger research question. From a 2008 sample of Subreddits, "Worldnews," "News," and "Politics," which grammatical adjectives and grammatical verbs co-occure with different pronouns? What kinds of actions are associated with male and female pronouns? And, how are different genders described in these Subreddits? 

Finds (enter image)


**Week 10** uses log likelihood to measure "distinctiveness" in a sample data set of quarterly reports on American corporations from EDGAR. Students process the data using tools from the scikit-learn module of statistics and machine learning, while focusing on count vectorizorization. They produce multiple visualizations for comparing and analyzing the distinct words in the quartery reports. 

**Week 12**