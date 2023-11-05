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

[Train my first image classifier! ](/marcelle/ml-webcam){: .btn }

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



## Train your model in Python

## Create your own interactive ML web application