---
pdf: "./salakhutdinov12a/salakhutdinov12a.pdf"
title: One-Shot Learning with a Hierarchical  Nonparametric Bayesian Model
abstract: "We develop a hierarchical Bayesian model that learns categories from single
  training examples. The model transfers acquired knowledge from previously learned
  categories to a novel category, in the form of a prior over category means and variances.
  The model discovers how to group categories into meaningful super-categories that
  express different priors for new classes. Given a single example of a novel category,
  we can efficiently infer which super-category the novel category belongs to, and
  thereby estimate not only the new categoryâ\x80\x99s mean but also an appropriate
  similarity metric based on parameters inherited from the super-category. On MNIST
  and MSR Cambridge image datasets the model learns useful representations of novel
  categories based on just a single training example, and performs significantly better
  than simpler hierarchical Bayesian approaches. It can also discover new categories
  in a completely unsupervised fashion, given just one or a few examples."
layout: inproceedings
key: salakhutdinov12a
month: 0
firstpage: 195
lastpage: 206
origpdf: http://jmlr.org/proceedings/papers/v27/salakhutdinov12a.pdf
sections: 
authors:
- given: R.
  family: Salakhutdinov
- given: J. Tenenbaum A.
  family: Torralba
---