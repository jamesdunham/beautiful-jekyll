---
layout: page
title: Code
published: true
---

## qsurvey

[qsurvey](../qsurvey) is a toolkit for working with
the [Qualtrics](https://www.qualtrics.com/research-suite) platform and its survey
data in R. Download responses and designs directly into a session, then:

* Examine branching, randomization, and question attributes like validation
* Represent survey flows as directed graphs for interactive review in Shiny
* Map question ids to labels and translate between choice
  codes and descriptions in response data

See more at the [project page](../qsurvey).

## dgo

[dgo](../dgo) is an R package for dynamic estimation of group-level opinion with multilevel Bayesian models. It implements a method for estimating subpopulation groups' average conservatism (or other trait) from individuals' responses to dichotomous questions.

The method is dynamic both in the sense that groups are allowed to evolve over time and in the sense that the model borrows strength from other time periods, to a degree specified by the user. [This document](https://github.com/jamesdunham/dgo/blob/master/inst/dgirt_details.pdf) describes the model in detail. It is a modification of the hierarchical group-level IRT model implemented by Devin Caughey and Christopher Warshaw in ["Dynamic Estimation of Latent Opinion Using a Hierarchical Group-Level IRT Model"](http://pan.oxfordjournals.org/content/early/2015/02/04/pan.mpu021.full.pdf+html) (*Political Analysis* 2015).
