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

This post provides an overview of the material used by "Text Mining as Historical Method." For full course materials, including interactive Jupyter Notebooks used by the class, see the [digital-history](https://github.com/stephbuon/digital-history) repository. 

Becuase this class encourages exploration of discourses that shape our culture, for their own research projects studens have access to various data sets including: Reddit posts from the Push Shift API (2008-2015); the 19th-century Hansard Parliamentary debates of Great Britain; The Stanford Congressional Records; The Dallas and Houston City Council Minutes; literature from Project Gutenberg, metadata from the NovelTM Datasets for English-Language Fiction, 1700-2009, and corporate reports from EDGAR, the Electronic Data Gathering, Analysis, and Retrieval system. 

The skills practiced in this course begin with basic word counts and visualization techniques and extend to the high-level application of ML modules to tell digital history, such as spaCy, sci-kit learn, and gensim word embeddings. By the end of the course students are able to perform comparative analyses and observe how langauge chnages over time. 

### Course Overview

**Week 1** provides an introduction to GitHub and JupyterLab. It also prepares students to work on Southern Methodist University's mainframe computer, M2. Students learn basic `git` commands to clone and pull from the [digital-history](https://github.com/stephbuon/digital-history) repository, and they set up their coding environment on M2 to run the JupterNotebooks for class. 

**Week 2** covers basic programming concepts in Python such as for loops and indexing elements. At the end of the Notebook, students are equipt to perform a basic wordcount of text from the Old Bailey and visualize their counts with a bar chart. 

**Week 3** introduces basic concepts in textual analytics and natural language processing such as stemming, lemmatization, regular expressions, and n-grams for bag-of-words analysis. Students process text by lemmatizing or stemmming it, and then divide text into tokens or bigrams. With bigrams, students use regular experssions to match with n-grams that contain a word of interest. This activity is useful for understanding word co-occurance in text.

**Week 4** 


**Week 5** demonstrates working with tabular data and date time types. Students break dates into just their years, or their years and months. Students also find a period's decade and group text belonging to each decade. After this overview of working with dates, students render a dot plot that follows the conventions for visualizing time data: time is treated on the x-axis, with years in sequential order. 

**Week 6**

**Week 8**

**Week 9** uses spaCy to answer a guided research question. From a 2008 sample of Subreddits, "Worldnews," "News," and "Politics," which grammatical adjectives and grammatical verbs co-occure in discourses about different genders? What kinds of actions are associated with male and female pronouns? What adjectives are used to describe men and women?  

Finds (enter image)

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/top-f-pronoun-verb-counts.png">
    <img src="/images/top-m-pronoun-verb-counts.png">
    <img src="/images/top-f-adj-noun-counts.png">
    <img src="/images/top-m-adj-noun-counts.png">
  </div>
  <em>Gallery / <a href="https://unsplash.com/" target="_blank">Unsplash</a></em>
</div>

**Week 10** uses log likelihood to measure "distinctiveness" in a sample data set of quarterly reports on American corporations from EDGAR. Students process the data using tools from the scikit-learn module of statistics and machine learning, while focusing on count vectorizorization. They produce multiple visualizations for comparing and analyzing the distinct words in the quartery reports. 

**Week 11** 

**Week 12**