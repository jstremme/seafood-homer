---
layout: post
title:  "Pretraining Federated Text Models for Next Word Prediction"
date:   2020-05-16 18:00:00
categories: Data-Science
---

In the winter of 2020, I completed my MS in data science and my capstone project on pretraining neural networks for federated next word prediction.  The focus of this work was to contribute research to the growing field of [Federated Learning](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html), to which I was introduced during my machine learning course, DATA558 at University of Washington.  [Brendan McMahan](https://research.google/people/author35837/), a principal researcher in Federated Learning, gave a guest lecture on his work at Google on [training federated deep learning models](https://arxiv.org/abs/1602.05629) which sparked my interest in the topic.  My enterprising classmate and soon to be research partner followed up with Brendan after the lecture.  This led to a project the following academic year in which he and I worked with two project sponsors from the Google Federated Learning team to conduct research in the field and contribute experimental findings to their ongoing work.

My research focused on pretraining methods for federated deep learning models designed for next word prediction, an important area of applied research for federated learning, as Google mobile keyboards use Federated Learning to train models to predict words in text messages, helping not only to complete our thoughts, but if you ask me, to more importantly, offer suggestions for correctly spelled words.  With the Google keyboard just early application of Federated Learning, there are many open areas for this area of research to impact our lives, particularly in healthcare where data is often distributed but private, silod across various providor, payer, and research insitituions.

mentors on the Federated Learning team at Google, and help from our professor at UW.  You can check out the [code](https://github.com/federated-learning-experiments/fl-text-models) and [paper](https://arxiv.org/abs/2005.04828) for the project here. The paper is on arXiv but not yet published with peer-review.

In future blog posts I intend to write about my experience writing a research paper, building an open source codebase for a particular data science task, and human-centered considerations for data science work.  I may also feature open-source projects I'm working on or have completed that.
