---
toc: true
layout: post
image: images/ml_logo.png
description: My First Blog Post on Machine Learning.
categories: [markdown, machine-learning]
title: Hands on ML Made Easy course on YouTube
sticky_rank: 1
---


# Introduction
---

> **Note:** This post is for beginners who want to learn Machine Learning through python coding and for those who want a structured video lectures of the book, **[Hands-On Machine Learning with Scikit-learn, Keras and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)**. For advanced users, I would suggest going through the _[curriculum in Notion](https://rural-sapphire-cce.notion.site/O-Reilly-Hands-On-ML-Book-Curriculum-d6952ef1dd914ed19553a6235d0ee948)_ for your own use case.

> If you want a visual understanding then I would suggest following the [short video](https://youtu.be/S1F7gy-UK7I) on my youtube channel giving an overview of the series:

<iframe width="560" height="315" src="https://www.youtube.com/embed/S1F7gy-UK7I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"> </iframe>

Hello World! I am Aditya Ramesh Ganti, a nerd-y (probably the word dosen't exist, but nevermind!) student pursuing my B.Tech degree in Smart Manufacturing at PDPM Indian Institute of Information Technology, Design and Manufacturing, Jabalpur (wow, that's a mouthful!😅 You can call it [PDPM IIITDMJ](https://www.iiitdmj.ac.in/)). Jabalpur is a city in Madhya Pradesh, India.

I am a Machine Learning and Robotics Entusiast aiming to be one of the best in the field. I love doing research irrespective of the subject and gain knowledge, whether I remember it or not is secondary, though 😅. I have been learning Machine Learning and a little bit of Robotics for the past year and a half. And I thought I'd share my learning through the series of videos that I will be uploading weekly every Sunday starting today on my [YouTube Channel](https://www.youtube.com/channel/UCXF74-jFED_EYHGuL5HxvGQ). The series provides explanation of the concepts and do hands-on code provided in the book through Jupyter Notebook. All the code will be available in my [github repo](https://github.com/ARGF0RCE/Hands-On-ML-Made-Easy) to get along with the videos. Though, the repo is still under development, all the code that were recorded will be provided before-hand.

# Prerequisites

A pinch of Python and a touch of some familiar Python's scientific libraries - [Numpy](https://numpy.org), [Pandas](https://pandas.pydata.org/), and [Matplotlib](https://matplotlib.org).

Also if you care about what is happening behind the scenes, you should have a reasonable understanding of college-level math as well. Khan Academy is a good place to brush up your math skills.

If you want a whole roadmap of what to learn to become a Machine Learning Engineer, I'd recommend the [roadmap](https://whimsical.com/machine-learning-roadmap-2020-CA7f3ykvXpnJ9Az32vYXva) made by [Mr. Daniel Bourke](https://www.mrdbourke.com/) who is a self-learned Machine Learning engineer and is also one of my inspirations for creating content regarding the same. Thank you for all the hard work Mr. Bourke, looking forward to more [videos](https://www.youtube.com/channel/UCr8O8l5cCX85Oem1d18EezQ/videos) of yours.

# Why this course?

Actually I posted a discussion on his GitHub repo for the [TensorFlow Deep Learning Course](https://zerotomastery.io/courses/learn-tensorflow/), regarding this series of videos...

<img width="953" alt="image" src="https://user-images.githubusercontent.com/86123710/172115124-309a6ebf-d6b3-4198-8e7c-9f28ad2023e9.png">

And that's how it went. And I plan on following what he suggested. I am going to inspire you to do research *on your own*. There is Google to answer our prayers!

![JustGoogleItBroAllGasNoBrakesGIF](https://user-images.githubusercontent.com/86123710/172115467-23b0a3d5-a49d-4881-96a2-508e6861c26d.gif)

So this course is going to cover as much as it can but also give you extra-curriculum activities which you need to google. Of course, it is not compulsory but it is always beneficial to be out of the comfort zone and take the initiative. 😎

Hence, this course is going to be beneficial in not only gaining knowledge of Machine Learning, but also the methods of self-learning.

# O’Reilly Hands-On ML Book Curriculum that we'll be covering

# Status

- Finished chapter 1 June 3, 2022
- Starting Chapter 2 June 3, 2022 1:04 PM

## Part 1:

- [x]  The Machine-Learning Landscape
- [x]  End-to-End Machine Learning Project
- [ ]  Classification
- [ ]  Training Models
- [ ]  Support Vector Machines
- [ ]  Decision Trees
- [ ]  Ensemble Learning and Random Forests
- [ ]  Dimensionality Reduction
- [ ]  Unsupervised Learning Techniques

## Part 2:

- [ ]  Introduction to Artificial Neural Networks with Keras
- [ ]  Training Deep Neural Networks
- [ ]  Custom Models and Training with TensorFlow
- [ ]  Loading and Pre-processing Data with TensorFlow
- [ ]  Deep Computer Vision Using Convolutional Neural Networks
- [ ]  Processing Sequences using RNNs and CNNs
- [ ]  Natural Language Processing with RNNs and Attention
- [ ]  Representation Learning and Generative Learning using Autoencoders and GANs
- [ ]  Reinforcement Learning
- [ ]  Training and Deploying TensorFlow Models at Scale

## Part 3:

- [ ]  Machine Learning Project Checklist
- [ ]  SVM Dual Problem
- [ ]  Autodiff
- [ ]  Other Popular ANN Architectures
- [ ]  Special Data Structures
- [ ]  TensorFlow Graphs

# The Machine Learning Landscape

Assign: Aditya Ramesh Ganti
Date: June 2, 2022 13:00-15:00
Status: Completed - June 2022

## 1. What is Machine Learning?

- Machine Learning is the science and art of programming a computers so that they can *learn from data*.

## 2. Why use Machine Learning?

- It is difficult to write and maintain a traditional program for the problem of spam filter as the input varies every time.
- Instead predicting through some given key words by a Machine Learning algorithm is much easier. Hence comes the use of machine learning.
- Also, machine learning can help humans learn about the various possibilities that can occur in an event given the few dependent features.

To summarize, Machine Learning is great for:

- Problems for which existing solutions require a lot of fine-tuning or long lists of rules: one Machine Learning algorithm can often simplify code and perform better than the traditional approach.
- Complex Problem for which using a traditional approach yields no good solution: the Best Machine Learning techniques can perform better than the traditional approach.
- Fluctuating environments: a Machine Learning system can adapt to new data.
- Getting insights about complex problems and large amounts of data.

## 3. Examples of Applications

1. **Analyzing images of products on a production line to automatically classify them**
2. **Detecting tumors in brain scans**
3. **Automatically classifying news articles**
4. **Detecting credit card fraud**
5. **Building an intelligent bot for a game**

and much more…

## 4. Types of Machine Learning Systems

There are so many different types of Machine Learning Systems that it is useful to classify them in broad categories, based on the following criteria:

- Whether or not they are trained with human supervision
- Whether or not they can learn incrementally on the fly.
- Whether they work simply by comparing new data points, or instead by detecting patterns in the training data and building a predictive model, much like scientists do.

### 4.1 Supervised/Unsupervised Learning

Machine Learning systems can be classified according to the amount and type of supervision they get during training. There are four major categories: supervised learning, unsupervised learning, semi-supervised learning, and Reinforcement learning.

### 4.1.1 Supervised Learning

In *supervised learning*, the training set you feed to the algorithm includes the desired solutions, called *labels*. 

Here are some of the most important supervised learning algorithms:

- k-Nearest Neighbors
- Linear Regression
- Logistic Regression
- Support Vector Machines (SVMs)
- Decision Trees and Random Forests
- Neural Networks

### 4.1.2 Unsupervised Learning

In *unsupervised learning* as you might have guessed, the training data is unlabeled. In simple words… The system tries to learn without a teacher.

Here are some of the most important unsupervised learning algorithms:

- Clustering
    - K-Means
    - DBSCAN
    - Hierarchical Cluster Analysis (HCA)
- Anomaly detection and novelty detection
    - One-class SVM
    - Isolation Forest
- Association rule learning
	- Apriori
	- Eclat
