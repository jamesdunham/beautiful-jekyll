---
layout: page
title: Code
---

## qsurvey

[qsurvey](https://github.com/jamesdunham/qsurvey) is a toolkit for working with
the Qualtrics platform and its survey data in R. Download responses and designs
into a session, then:

* Represent survey flows as directed graphs for interactive review in Shiny
* Validate branching and randomization with checks on the proportion of
  respondents who saw a question, conditional on having viewed others /
  given some response / embedded data
* Inspect question characteristics like validation, randomization, and recodes
* Map question ids to labels (`QID7` ⟷ `trust`) and translate between choice
  codes and descriptions (`2` ⟷ `disapprove`) in response data
* Use helper functions for other common tasks

## dgo

[dgo](https://github.com/jamesdunham/dgo) is an R package for dynamic estimation
of group-level opinion with multilevel Bayesian models. 
