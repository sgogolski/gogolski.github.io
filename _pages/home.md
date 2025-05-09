---
layout: single
permalink: /
hidden: true
header:
  #image: /assets/images/header.jpeg
  #overlay_color: "#5e616c"
  #overlay_image: /assets/images/fog_road.jpeg
title: " "
tagline: " "
author_profile: true
classes: wide

feature_row1:
  - image_path: assets/images/0619CED0-FE46-4E25-A039-A703433FC1B5_1_105_c.jpeg
    alt: "Resources"
    excerpt: "Explore helpful course materials."
    url: "/resources/"
    btn_class: "btn--inverse"
    btn_label: "Explore Resources"

feature_row2:
  - image_path: assets/images/4C9008C8-D14E-4699-8430-C781C1FB0B43_1_105_c.jpeg
    alt: "Lectures"
    excerpt: "Favorite and featured lecture modules from CM515."
    url: "/lectures/"
    btn_class: "btn--inverse"
    btn_label: "View Lectures"

feature_row3:
  - image_path: assets/images/image_2.png
    alt: "Image"
    excerpt: "Learn how we analyzed microscopy images using Cell Profiler."
    url: "/Image/"    # ✅ uppercase 'I'
    btn_class: "btn--inverse"
    btn_label: "See Project"


feature_row4:
  - image_path: assets/images/ggplot.png
    alt: "ggplot"
    excerpt: "Explore our visualizations using ggplot2."
    url: "/ggplot/"
    btn_class: "btn--inverse"
    btn_label: "View Visuals"
---

Portfolio of materials from [CSU CM515](https://github.com/Colorado-State-University-CMB/CM515-course-2025/tree/main)!

# Resources
{% include feature_row id="feature_row1" type="center" %}

# Lectures
{% include feature_row id="feature_row2" type="center" %}

# Image 
{% include feature_row id="feature_row3" type="center" %}

# ggplot
{% include feature_row id="feature_row4" type="center" %}



