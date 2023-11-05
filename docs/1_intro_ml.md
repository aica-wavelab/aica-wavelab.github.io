---
layout: default
title: 1. Introduction to machine learning
nav_order: 4
permalink: /docs/1_intro_ml
---

# Introduction to machine learning
{: .no_toc}


This chapter will teach you foundational concepts of machine learning (ML) through hands-on turorials.
The first three chapters only use interactive applications, no programming skills are required.
The fourth chapter reiterates the same concepts using programming tools that prevail in the ML industry, namely the Python programming language and dedicated ML libraries.
Lastly, the fifth section provides ressources to develop your on web-based interactive ML application, using the [Marcelle](https://www.marcelle.dev) toolkit.

{: .note-title }
> Tips
>
> We recommend to all attendants to follow the first four sections.

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Train your first image classifier

Have you ever trained a machine learning model ? If not, this is the right place to start.
First of all, what is a machine learning?

{: .note-title }
> Definition
>
> Machine learning (ML) is a field of study in artificial intelligence concerned with the development and study of statistical algorithms that can effectively generalize from examples and thus perform tasks without explicit instructions.

In other words, machine learning (ML) part of the field of AI but its specificity lies in the fact that algorithms are learning from data.
To give you a concrete example, let's train your first image classifier from images collected with your webcam and using the application below.

[Train my first image classifier! ](/marcelle/ml-webcam){: .btn target="_blank"}

In this application, you can activate the `webcam` of your laptop on the left side of the screen. 
Below the `webcam`, you can choose a `label` to be associated with the images you will collect. Once the `label` selected, click on the button `hold to collect` to collect images with the corresponding `label`. Doing so, you will see the images you collect appearing in the `Training set` in the middle of the screen.
Reiterate this process for each `label` you want to collect images for. 

Once you finalized the creation of your `Training set` (images + corresponding labels), you can click on the button `Train` to train your image classifier.
Then, you can activate the `webcam` again and see the predictions of your image classifier in real-time in the component `Prediction confidence` on the bottom of the screen.

{: .note-title }
> Hints
>
> Take the time to test the model you trained. Try to trick its predictions and see how it reacts. What data could you add to the training set to improve its predictions?

You trained your first image classifier! Congratulations! 
But you don't know much about how machine learning works... Let's now see what's going on under the hood of this web application.

## The development cycle of ML

The development of ML is a cycle composed of 4 main steps. These steps are illustrated in the application below.
[The development cycle of ML](/marcelle/ml-vision){: .btn target="_blank"}

You can perform the different steps of the development cycle of ML in the application above and using different image datasets: 

- mini

### 1. Data collection

The first step of the development cycle of ML is data collection. It consists in collecting and annotating data samples that can be used by an ML algorithm to learn a mapping from inputs to outputs. In the previous example, the data samples are images collected with your webcam and the corresponding labels you provided.
If pairs of input and output are provided in the training set, we talk about **supervised learning**. If only inputs are provided, we talk about **unsupervised learning**.

The data samples are usually gathered in two sets: the **training set** and the **test set**. The training set is used to train the ML model, while the test set is used to evaluate the performance of the trained model. In other words, the training set is the exemples you work on during the semester, while the test set is the final exam.



### 2. 


## Train your model in Python

## Create your own interactive ML web application