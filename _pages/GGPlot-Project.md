---
layout: single
title: "GGPlot Project"
permalink: /ggplot-project/
classes: wide
author_profile: true
read_time: true
share: false
header:
  overlay_image: /assets/images/ggplot-header.jpg
  overlay_filter: 0.3
  caption: "Visualizations with ggplot2 in R"
---

## GGPlot Project Overview

Welcome to the **GGPlot Project** page. This is where you’ll find example code, explanations, and data visualizations created using the `ggplot2` package in R.

---

## Example Code (R)

```r
# Load required libraries
library(ggplot2)

# Use built-in dataset
data(mpg)

# Create scatter plot
ggplot(mpg, aes(x = displ, y = hwy, color = class)) +
  geom_point() +
  labs(
    title = "Engine Displacement vs. Highway MPG",
    x = "Displacement (liters)",
    y = "Highway MPG"
  ) +
  theme_minimal()


