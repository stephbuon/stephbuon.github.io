---
layout: post
title: 'The Hansard 19th-Century British Parliamentary Debates: Parsed Debates, N-Gram Counts, Special Vocabulary, and Topics'
description: Automated scripts for producing the SMU version of the Hansard data, parsing debates, counting n-grams, and dynamically modeling topics. 
date:   2020-11-12 15:01:35 +0300
image:  '/images/the_hansard_19th_century_british_parliamentary_debates.png'
tags:   [Hansard, History, Journal Article]
---
We present "The Hansard 19th-Century British Parliamentary Debates with Improved Speaker Names: Parsed Debates, N-Gram Counts, Special Vocabulary, Collocates, and Topics" an analysis-ready version of the 19th-century Hansard with supplementary materials. Our intention is to provide researchers with an analysis-ready version of the Hansard debates to enhance analyses of the era.

While we were aggregating this corpus, we made two major improvements: we identified debates that had missing entries in UK Parliament’s records and we added a field for the names of disambiguated speakers. Our process for disambiguated speakers is recorded as a separate project, <a href="https://stephbuon.github.io/speaker-name-disambiguation" style="color: blue"> here </a>. 

While creating this corpus we identified systematic issues within Parliament's digital version of the debates where XML tags were missing or erroneous. Debate text, for example, might be tagged as a debate title or as a speaker. In other cases, sections were missing tags in their entirety. While the mistagged data was merely buried, not lost to time, the errors in the XML tags were problematic enough to cause the data to miss being indexed by UK Parliament, and to result in missing entries from the corpus.

Automated scripts for producing our corpus can be found on <a href="https://github.com/stephbuon/hansard-corpus" style="color: blue"> our repository </a>. An article 
    
This work was supported in part by National Science Foundation (NSF) Grant (no. 1520103). 
