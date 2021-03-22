---
layout: post
title: Introduction to Machine Learning Concepts
comments: true
---

<div class="message">
  This is a work in progress. More will be added soon!
</div>

## The Problem Setting

A typical learning problem considers a set of unknown data samples and tries to predict the data's properties. If each sample is more than a single number (a multi-dimensional entry aka multivariate data), it is said to have several <em>attributes</em> or <em>features</em>.

We can separate common learning problems in two large categories: <em>supervised learning</em> and <em>unsupervised learning</em>.

## Supervised learning

In supervised learning, the data set comes with additional attributes, a piece of information that determines the properties we want to predict. Problems can be either classification or regression.

In classification problems, samples belong to two or more classes. We want to learn from already labeled data how to predict the class of unlabeled data. An example of classification problem would be handwritten letter recognition. Another way to think of classification is as a discrete form of supervised learning where one has a limited number of categories and for each of the `n` samples provided, one tries to label them with the correct category or class.

In regression cases, the desired output consists of one or more continuous variables. An example would be the prediction of the price of a house based on several significant parameters like number or rooms and area.

## Unsupervised Learning

In unsupervised learning, the training data consists of a set of input vectors `x` without any corresponding target values. The goal in such problems may be to discover groups of similar examples within the data &mdash; this is known as <em>clustering</em>. Another objective could be to determine the distribution of data within the input space, known as density estimation, or to project the data from a high-dimensional space down to two or three dimensions for visualization.
