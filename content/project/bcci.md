+++
# Date this page was created.
date = "2017-07-06"

# Project title.
title = "Cricket Data Scraper"

# Project summary to display on homepage.
summary = "Web Scraper for BCCI and IPLt20 website"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "boards.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["parallel-computing", "poisson-solver"]`
tags = ["Web-Scraping"]

# Optional external URL for project (replaces project detail page).
external_link = ""

[header]
image = "headers/bubbles-wide.jpg"

# Does the project detail page use math formatting?
math = false

+++

This project was undertaken by me during my intern period at <a href="//seehow.io/">SeeHow</a>. The aim was to get speed data for various bowlers which can be later used for benchmarking in the product. The code gets data from <a href="//bcci.tv/">bcci</a> and <a href="//iplt20.com">ipl</a> websites. 

The backend uses selenium to get data from the websites and stores in a sqlite database. A query system was also made to get different kinds of data from the database. Then python framework flask was used to change the code into a webapp.

Feel free to contact me to know more. 