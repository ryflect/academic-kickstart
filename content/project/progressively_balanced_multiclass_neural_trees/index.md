+++
title = "Progressively Balanced Multi-class Neural Trees"
date = 2017-08-01
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["decision trees","ML","classification","tensorflow","python"]

# Project summary to display on homepage.
summary = "Proposed and tested an entropy impurity based objective function for incorporating a learnable perceptron into the decision tree framework. Demonstrated that the learned classifier achieves comparable accuracy with fewer test time computations than an MLP"

# Optional image to display on homepage.
image_preview = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Does the project detail page use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
**Mentor:** Dr. Prithwijit Guha (Dept. of EEE, IIT Guwahati)

**Collaborator:** Spoorthy Bhat

This project was my Bachelor's thesis at IIT Guwahati.

The basic idea is to allow each node to learn **oblique partitions** in the input space as opposed to the axis-aligned partitions learned by a standard **C4.5** tree. This required the development of a differentiable criterion.

During the course of the project we realized that this hierarchical partitioning results in **data-thinning** (i.e. as we go down the tree, the number of samples reaching a node go on decreasing). This causes the trained nodes to be biased when class distributions become unbalanced. Consequently, we resort to **data balancing**. We tested different methods of artificially balancing the class distribution in the data at each node.

Our method gave comparable accuracy to existing classifiers on 10 benchmark datasets. *What is the gain?* The learned trees require fewer computations at test time (on average over the test set) than a multi-layer perceptron (MLP) of comparable accuracy.

We designed the framework for training the decision tree and node parameters, and testing the classifier using the Tensorflow package.