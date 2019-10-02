+++
title = "Autonomous Intelligent Robot"
date = 2015-04-01
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["planning","SLAM","ROS"]

# Project summary to display on homepage.
summary = "Implemented simultaneous localization and mapping (SLAM) and visual odometry to create a robot capable of mapping and navigating its environment."

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

The Robotics Club of IIT Guwahati developed this project. The aim was to learn on the go which was facilitated through tutorials by senior members of the club and the institute as a whole. The project resulted in a robot that could:

- **Map** its environment and create a 3D rendering of the world using a stereo-camera (which provided depth information). We later migrated to the Kinect sensor
- **Localize** itself in a known map upon initialization
- **Navigate** to a given target location (set in the map)

The software was built on top of the **Robot Operating System (ROS)** which provide packages for handling all the concurrent processes.