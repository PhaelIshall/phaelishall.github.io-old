---
title: "Extracting Non-traditional Features to Predict Readability"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - NLP
  - ML 
---

![readability](https://user-images.githubusercontent.com/13065761/151680387-2269ab68-8cbb-4e3d-bb11-a1ca2c7c6106.png)

## Project Motivation
The success of a supervised learning task like predicting readability comes primarily from the
development of a strong set of features. There are many common features used to predict
readability that were not necessarily designed for supervised learning, and do not map well to
our dataset (e.g. Flesch–Kincaid). Due to the highly specialized and complex nature of
medical abstracts, our approach required the development of features more custom to the
problem and more fine-grained in discriminating between various levels of difficulty.
In the feature selection we relied on a research paper titled “A Comparison of Features for
Automatic Readability Assessment” [1], as well as adjusting the features mentioned below to
match the medical nature of the excerpts.


*[1] Lijun Feng, Martin Jansche, Matt Huenerfauth, Noemie Elhadad, “A Comparison of
					Features for Automatic Readability Assessment”, Coling 2010: Poster Volume, pages
					276–284, Beijing, August 2010*
          
## Resources
[Github](https://github.com/PhaelIshall/hw3_Computational_Linguistic)

[Leaderboard](https://www.cis.upenn.edu/~cis530/leaderboard.htm)

<!--more-->
