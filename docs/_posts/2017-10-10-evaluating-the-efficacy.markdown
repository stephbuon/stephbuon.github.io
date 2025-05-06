---
layout: post
title: 'Evaluating the Efficacy of LLMs to Emulate Realistic Human Personalities'
description: To improve the realism of affective Non-Player Characters (NPCs) in video games, this study investigates whether Large Language Models (LLMs) can emulate human personalities. Using the Big Five framework and over 50,000 responses from the International Personality Item Pool (IPIP), LLMs were prompted with self-assessment items corresponding to various personality profiles. Their outputs were then compared to human baseline responses to evaluate accuracy and consistency. Results showed that while some local models exhibited 0% alignment with human profiles, certain frontier models achieved 100% alignment. These findings suggest that LLMs can effectively replicate human-like personality traits, providing a method for evaluating and designing NPCs with more realistic, personality-driven behavior.
date:   2017-10-10 15:01:35 +0300
image:  '/images/personality.png'
tags:   [Artificial Intelligence]
---
We present "The Hansard 19th-Century British Parliamentary Debates with Improved Speaker Names: Parsed Debates, N-Gram Counts, Special Vocabulary, Collocates, and Topics." Our intention is to provide researchers with an analysis-ready version of the 19th-century Hansard debates (and supplementary material) to enhance analyses of the era.

We made two major improvements while creating this corpus: we identified debates that had missing entries in UK Parliament’s records and we added a field for the names of disambiguated speakers. Our process for disambiguated speakers is recorded as a separate project, <a href="https://stephbuon.github.io/speaker-name-disambiguation" style="color: blue"> here </a>. 

To discover missing debates we identified systematic issues within Parliament's digital version of Hansard where XML tags were missing or erroneous. Debate text, for example, might be tagged as a debate title or as a speaker. In other cases, sections were missing tags in their entirety. While the mistagged data was merely buried, not lost to time, the errors in the XML tags were problematic enough to cause the data to miss being indexed by UK Parliament, and to result in missing entries from the corpus.

Automated scripts for producing our corpus can be found on <a href="https://github.com/stephbuon/hansard-corpus" style="color: blue"> our repository </a>. An article 
    
This work was supported in part by National Science Foundation (NSF) Grant (no. 1520103). 
