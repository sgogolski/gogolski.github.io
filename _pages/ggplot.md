---
layout: single
permalink: /ggplot/
title: "ggplot Resources"
tagline: "Visualizations, guides, and downloads for CM515"
author_profile: false
read_time: true
classes: wide
header:
  overlay_image: /assets/images/ggplot2-banner.png
  overlay_filter: 0.3
  caption: "Visualizing Data with ggplot2"
---

## Overview

**ggplot2** is a powerful R package for creating elegant data visualizations. This page includes datasets, reference materials, and external tools to support your learning.

---

## Downloads

- 📊 [**Dataset A (CSV)**](/resources/files/dataset_a.csv)
- 📄 [**Reference Sheet (PDF)**](/resources/files/ref_sheet.pdf)

---

## External Resources

- 🌐 [**R for Data Science**](https://r4ds.had.co.nz/index.html): Using RStudio for Data Analysis

---

## Example Output

Here’s what a basic `ggplot2` visualization looks like:

```r
library(ggplot2)
ggplot(mtcars, aes(x = wt, y = mpg)) +
  geom_point() +
  theme_minimal()



