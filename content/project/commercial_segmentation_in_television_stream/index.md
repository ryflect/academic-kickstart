+++
title = "Commercial Segmentation in Television Stream"
date = 2017-06-01
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["video processing","image processing","ffmpeg"]

# Project summary to display on homepage.
summary = "Attempted segmentation of commercials in television stream through audio-visual feature engineering and application of sequence classifier."

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

The problem of detecting when a television stream has switched from content to commercials (advertisements) is difficult because of the wide range of presentation formats available. Even trickier is detecting inter-commercial transitions. Once these transitions are accurately predicted, methods can be developed to further identify the product being advertised. This problem is of importance to companies and advertisers both, as it helps provide credibility to the claimed number times a particular commercial was broadcasted.

Boiled down to the basics: *the project aimed at developing a classifier that could accurately predict whether a scene change resulted in the start/end of a commercial.*

The project is being developed by the **Multimedia Analytics Lab (IIT Guwahati)**. I participated in the project as a student intern. My role involved **collecting and cleaning a dataset, structuring the experiments, and implementing baselines.**