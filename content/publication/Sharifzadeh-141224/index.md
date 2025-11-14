---
title: "Mitigating Aberration-Induced Noise: A Deep Learning-Based Aberration-to-Aberration Approach"
authors:
- Mostafa Sharifzadeh
- Sobhan Goudarzi
- An Tang
- Habib Benali
- Hassan Rivaz
date: "2023-08-22T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "One of the primary sources of suboptimal image quality in ultrasound imaging is phase aberration. It is caused by spatial changes in sound speed over a heterogeneous medium, which disturbs the transmitted waves and prevents coherent summation of echo signals. Obtaining non-aberrated ground truths in real-world scenarios can be extremely challenging, if not impossible. This challenge hinders the performance of deep learning-based techniques due to the domain shift between simulated and experimental data. Here, for the first time, we propose a deep learning-based method that does not require ground truth to correct the phase aberration problem and, as such, can be directly trained on real data. We train a network wherein both the input and target output are randomly aberrated radio frequency (RF) data. Moreover, we demonstrate that a conventional loss function such as mean square error is inadequate for training such a network to achieve optimal performance. Instead, we propose an adaptive mixed loss function that employs both B-mode and RF data, resulting in more efficient convergence and enhanced performance. Finally, we publicly release our dataset, comprising over 180,000 aberrated single plane-wave images (RF data), wherein phase aberrations are modeled as near-field phase screens. Although not utilized in the proposed method, each aberrated image is paired with its corresponding aberration profile and the non-aberrated version, aiming to mitigate the data scarcity problem in developing deep learning-based techniques for phase aberration correction."

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://arxiv.org/pdf/2308.11149"

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

