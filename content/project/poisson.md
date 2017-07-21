+++
# Date this page was created.
date = "2017-07-06"

# Project title.
title = "Poisson Equation Solver"

# Project summary to display on homepage.
summary = "Multi grid solver for Poisson Equation"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "poisson.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["parallel-computing", "poisson-solver"]`
tags = ["Parallel-Computing"]

# Optional external URL for project (replaces project detail page).
external_link = ""

[header]
image = "headers/poisson.png"

# Does the project detail page use math formatting?
math = false

+++

This summer project was an intensive application of the concepts learned in the earlier n-body simulation project.

The aim was to create a multi-grid solver for the Poisson’s equation. The project was supervised by professor M.K. Verma. The existing serial code was changed into parallel approach to get the three dimension grid of unknown values in a Jacobian iterator method. The reason was the same that a parallel approach using GPUs could provide much greater computational speeds.


Belows is the link for the github repository of the code. Feel free to contact me to know more about it.

<a href="//github.com/AkashKrDutta/multigrid">Repository</a>