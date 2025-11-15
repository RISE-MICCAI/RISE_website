---
title: "Robust T-Loss for Medical Image Segmentation"
authors:
- Alvaro Gonzalez-Jimenez
- Simone Lionetti
- Philippe Gottfrois
- Fabian Gröger
- Marc Pouly
- Alexander Navarini

date: "2024-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: |
  **Speaker:** Alvaro Gonzalez-Jimenez

  This paper presents a new robust loss function, the T-Loss, for medical image segmentation. The proposed loss is based on the negative log-likelihood of the Student-t distribution and can effectively handle outliers in the data by controlling its sensitivity with a single parameter. This parameter is updated during the backpropagation process, eliminating the need for additional computation or prior information about the level and spread of noisy labels. Our experiments show that the T-Loss outperforms traditional loss functions in terms of dice scores on two public medical datasets for skin lesion and lung segmentation. We also demonstrate the ability of T-Loss to handle different types of simulated label noise, resembling human error. Our results provide strong evidence that the T-Loss is a promising alternative for medical image segmentation where high levels of noise or outliers in the dataset are a typical phenomenon in practice. The project website can be found at https://robust-tloss.github.io

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://arxiv.org/pdf/2306.00753"

url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
projects: []

# Slides (optional).
slides: ""
---

