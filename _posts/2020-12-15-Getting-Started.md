---
layout: post
title: Getting Started!
---

# Named Entity Recognition using Tensorflow

This is the first article in a series where we will go through our journey to discover building machine learning models in Python using the Tensorflow framework to solve the problem of Named Entity Recognition.

Here is an index of all the articles in the series that have been published to date:

* Part I: Getting Started (this article)

## Named Entity Recognition

It is the task of identifying categories such as name, organization, location on unstructured documents.

Before diving deep into the process of named entity recognition, we are going to start with a simple program that we can build and improve as time goes. In this way, it is going to act as a template for building software.

## Data Format

The most popular format for named entity recognition task is the CoNLL2003 dataset:

Ian Goodfellow works for Google Deepmind
B-Per I-Per          O     O     B-Org	I-Org

## Training

Instead of building a neural network and tuning hyperparameter, we are going to start slowly by first preprocessing our dataset into the format of Named Entity Recogntion and observing the result we get. So simply preprocess the data that you have in the format of train, validation, and test in text file format.

Ian B-Per
Goodfellow I-Per
works O
for O
Google B-Org
Deepmind I-Org

Put them in the `data/` directory and train the model.






Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

The easiest way to make your first post is to edit this one. Go into /_posts/ and update the Hello World markdown file. For more instructions head over to the [Jekyll Now repository](https://github.com/barryclark/jekyll-now) on GitHub.
