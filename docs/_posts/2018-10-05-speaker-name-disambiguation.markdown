---
layout: post
title:  Speaker Name Disambiguation in the Hansard 19th-Century British Parliamentary Debates
description: A pipeline for disambiguating speaker names in the 19th-century British Parliamentary debates. This project was supported by National Science Foundation (NSF) Grant (no. 1520103).
date:   2020-11-14 15:01:35 +0300
image:  '/images/speaker-name-disambiguation.png'
#video_embed: https://www.youtube.com/embed/gghgYaYeG_M
tags:   [History, Hansard]
---
Accurate analyses of legislative debates often rely on information about which individual was associated with which speech–the “speaker” field in the data. Analysis of speakers has been used, for example, to track the emergence of modern party discipline and to make claims about speaker influence. The accuracy of such analyses as these, however, can be thwarted by messy data.

We identify and correct for seven major causes for ambiguous speaker names: 1) speakers may have been called by temporary office titles (like “Prime Minister) instead of their real name; 2) speakers may have been called by their peerage titles (such as “Duke,” or “Viscount” instead of their real name); 3) a single name might have several permutations (such as W. Gladstone, W. E. Gladstone, or William Gladstone all referring to the same Mr. Gladstone); 4) speakers may have shared the exact name with someone else who was active during the same period (like the two MPs named Sir Robert Peel in the early 19th-century); 5) speaker names may have OCR errors, rendering them unrecognizable by the computer; 6) speaker names might have spelling inconsistencies due to how they were originally recorded during the 19th-century; and 7) some speakers were misrecorded, such as they were called by the wrong title.

See our <a href="https://github.com/stephbuon/hansard-speakers" style="color: blue"> repository on GitHub </a> for a copy and to run our pipeline. Read about our process (coming soon).  

This work was supported in part by National Science Foundation (NSF) Grant (no. 1520103). 
