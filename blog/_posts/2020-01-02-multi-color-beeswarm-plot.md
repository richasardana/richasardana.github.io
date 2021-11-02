---
layout: post
title: "Representing reproducibility and variability"
description: ""
author_handle: richa
category: blog
tags: [journal club, P values,Statistical analysis,Beeswarm plot, multi-colored dot plot,  Superplot]
image: /assets/images/blog/Lord-arxiv-2019-Fig1.png
---


*Research Paper Highlight:*
 **If your P value looks too good to be true, it probably is: Communicating reproducibility and variability in cell biology.**


Samuel J. Lord, Katrina B. Velle, R. Dyche Mullins and Lillian K. Fritz-Laylin [arXiv:1911.03509v2 (2019)](https://arxiv.org/abs/1911.03509)

Later published as a Viewpoint in [J Cell Biol (2020) 219 (6): e202001064.
DOI:10.1083/jcb.202001064](https://pubmed.ncbi.nlm.nih.gov/32346721)

<!--more-->

Cell biologists are no strangers to data variability- growth conditions, age of the cells, and nutrient availability all contribute to sample-to-sample differences. Accurate quantitative analysis and representation of cell biological measurements should ideally be able to reflect the number of times the experiment was repeated, the variability observed within each replicate set for individual measurements, and the key statistical identifiers for each set.

In this preprint, Lord et al, present a convincing case to represent cell biological quantitative data as multi-colored beeswarm or superplots to accurately reflect actual data quality, reproducibility and variability. 

Key highlights to note:

1. The problem of comically miniscule (and hence useless) P-values in many cell biology studies is in part due to erroneous and inflated sample size, N. N should represent the number of times an experiment is repeated, not the total number of cells.

2. Bar graphs are problematic because they obscure the distribution of cell-level data as well as the sample-to-sample repeatability.

3. Visual representation of the quantitation should represent variability information about the entire dataset whenever posible. This can be nicely accommodated into color-coded beeswarm SuperPlots. The authors provide detailed ways of making these plots using GraphPad Prism, Excel, R and Python. 


For example, if you have three biological replicates of control and treated samples, and you measure the speed of cellular movement of 200 cells in each sample, first calculate the mean of those 200 measurements for each sample, then run a t-test on those sample means (three control, three treated). In the data plot, color-coding the dots by experiment, and plotting the mean as a larger  symbol on top of the dots that denote individual measurements, makes it clear that statistical analyses (e.g. error bars and P values) are correctly calculated across separate experiments. 



