+++
title = "Bufferless Routeing in Network-On-Chip"
date = 2017-02-01
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["networks","OOP","C++"]

# Project summary to display on homepage.
summary = "Designed a network traffic simulator to study on-chip interconnection networks composed of bufferless routers."

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
**Mentor:** Dr. John Jose (Dept. of CSE, IIT Guwahati)

**Collaborators:** Nandan Bedekar, N Hariharan

On-chip interconnection networks are gaining popularity due increase in the number of cores on a processor chip. These networks allow multicore processing without the delays introduced by direct wiring. We modified the network traffic simulator [BookSim 2.0](http://nocs.stanford.edu/booksim.html) to study the properties of bufferless routers. In particular, we encoded the [**CHIPPER**](https://ieeexplore.ieee.org/document/5749724) architecture.

[**Project repository**](https://github.com/ameyagodbole/booksim2)