---
title: "SWAGex for Commonsense Validation and Explanation"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Natural Language Processing
  - Commonsense Reasoning
  - BERT 
  - Transformers 
---

![commonsense](https://user-images.githubusercontent.com/13065761/151680380-8d367cf0-8487-442b-a674-7ed3e9c1f445.jpeg)

## Project Motivation
Commonsense reasoning has long been a challenge in the field of Natural Language Processing (NLP). Recently, the emergence of large pre-trained language models achieving state-of-the-art results in several
NLP tasks, such as BERT and GPT has also influenced commonsense tasks to regain popularity.

Natural Language Inference (NLI) is one of the most popular tasks in commonsense reasoning research. It consists of determining if a hypothesis is correct, given a premise. Situations With Adversarial Generation (SWAG) task is closely related to NLI. It consists of determining the most appropriate ending given a start phase as a context. The start phrases and endings in SWAG dataset are video captions. The task is to find the ending that describes a possible (future) world that can follow the given sentence even when it is not strictly entailed. Making such inference necessitates a rich understanding of everyday physical
situations.

## Summary
- Used multiple methods on the pre-trained language model BERT to recognize sentences against commonsense and justify the reasoning behind this decision. 
- Investigated the ability to transfer commonsense knowledge from SWAG to ComVE task by training a model for the Explanation task with Next Event Prediction data.  

     ![1](https://user-images.githubusercontent.com/13065761/151681108-1bac2faf-030e-44d2-b38a-b701b1eb0bd1.png)
     ![2](https://user-images.githubusercontent.com/13065761/151681110-03301049-6762-482e-9b1d-f4fd3f27939d.png)


## Project Results
- Paper “SWAGex at SemEval-2020: Commonsense Explanation as Next Event Prediction", appeared in Proceedings of the 14th International Workshop on Semantic Evaluation.
- Poster presentation at COLING, in Dec 2020 (online)



<!--more-->
