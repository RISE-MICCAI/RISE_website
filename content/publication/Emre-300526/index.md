---
title: "Time Equivariant Representation Learning for Longitudinal Medical Images of Degenerative Diseases"
authors:
- Taha Emre
date: "2026-05-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal", "paper-conference", "article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging; MICCAI 2024; arXiv (under review)"
publication_short: "IEEE TMI; MICCAI 2024; arXiv"

abstract: |
  **Speaker:** Taha Emre

  Longitudinal medical imaging provides temporally ordered observations that can reveal disease trajectories. Standard self-supervised learning objectives often discard temporal information, while many longitudinal self-supervised methods assume explicit time-series input, which is less suitable for 3D volumetric data. We address this gap by framing longitudinal representation learning as world modeling in latent space, where visits are treated as states and inter-visit time differences as actions. This talk will cover time-sensitive representation spaces, time as a transformation, and uncertainty in future representations. First, we introduce a time-sensitive contrastive learning method that incorporates the time difference between visits [1]. Next, we extend this idea by directly learning temporal changes in representation space through a parameterized, learnable transformation [2]. Finally, our most recent self-supervised approach models uncertainty about future states using a conditional stochastic process in masked image modeling [3]. Together, these methods show how time can be treated not only as metadata, but as a structural signal for learning more informative representations from longitudinal medical images.

  [1] Emre et al. “3DTINC: Time-Equivariant Non-Contrastive Learning for Predicting Disease Progression from Longitudinal OCTs” IEEE TMI

  [2] Emre et al. “Learning Temporal Equivariance for Degenerative Disease Progression in OCT by Predicting Future Representations.” MICCAI, 2024

  [3] Emre et al. “Stochastic Siamese MAE Pretraining for Longitudinal Medical Images.” Under review, arXiv:2512.23441

  **About the speaker:** Taha Emre is a PhD candidate at the AI Institute, Medical University of Vienna, under the supervision of Hrvoje Bogunovic. He holds a BSc in Computer Engineering from Istanbul Technical University and an MSc in Computer Science from the Technical University of Munich. His research focuses on longitudinal representation learning in degenerative diseases, with an emphasis on retinal disease.

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: ""

links:
- name: "[1] IEEE TMI (3DTINC)"
  url: "https://ieeexplore.ieee.org/document/10507862"
- name: "[2] MICCAI 2024"
  url: "https://arxiv.org/abs/2405.09404"
- name: "[3] arXiv (STAMP)"
  url: "https://arxiv.org/abs/2512.23441"

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
