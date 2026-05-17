---
title: "Modeling DINO Embeddings for Fast and Efficient Unsupervised Anomaly Detection in Medical Imaging"
authors:
- Nico Schulthess
date: "2026-05-09T16:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "MICCAI 2025"
publication_short: ""

abstract: |
  **Speaker:** Nico Schulthess

  The goal of unsupervised anomaly detection (UAD) is to model the distribution of images from healthy patients and use this model to identify samples that deviate from the norm. UAD has made another leap using the rich, patch-level representations provided by foundational models like DINOv2 and DINOv3. However, traditional methods often rely on large memory banks of normative features, leading to significant computational and memory overhead during inference, which is particularly critical in medical imaging where the normative distribution shows more variance than in industrial vision applications. In this talk, we present two distinct yet complementary frameworks designed to move beyond raw feature storage toward more efficient and structured normative modeling.

  First, we explore a non-parametric approach using Dirichlet Process Mixture Models (DPMM) to learn the distribution of DINOv2 embeddings. By clustering DINOv2 embeddings, we automatically adapt the number of mixture components to the dataset, enabling fast, coarse anomaly detection without the need for an exhaustive memory bank.

  Second, we address the common oversight of spatial relationships in patch-level modeling. We introduce a Spatial Autoregressive (AR) model that uses a convolutional neural network to learn the distribution of DINOv3 embeddings and explicitly capture contextual dependencies between patches, enabling fast and memory efficient UAD with competitive performance.

  Together, these methods demonstrate that by modeling the distribution of foundational embeddings — either through probabilistic clustering or spatial autoregression — we can achieve competitive anomaly detection performance on medical benchmarks while substantially reducing inference time and hardware requirements.

  **About the speaker:** Nico Schulthess is a PhD student in the Biomedical Image Computing Group at ETH Zürich, under supervision of Prof. Ender Konukoglu. His main interest is to improve unsupervised anomaly detection in medical imaging and push towards efficient and scalable methods using foundation models. He previously completed his Master's and Bachelor's degree in Electrical Engineering at ETH Zürich with a focus on computer vision and machine learning.

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://papers.miccai.org/miccai-2025/paper/2425_paper.pdf"

links:
- name: arXiv
  url: "https://arxiv.org/abs/2603.02974"

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
