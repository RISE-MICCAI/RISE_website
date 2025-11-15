---
title: "MedFuncta: A Unified Framework for Learning Efficient Medical Neural Fields"
authors:
- Paul Friedrich
- Florentin Bieder
- Julian McGinnis
- Julia Wolleb
- Daniel Rueckert
- Philippe C. Cattin
date: "2025-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: |
  **Speaker:** Julia Wolleb

  Research in medical imaging primarily focuses on discrete data representations that poorly scale with grid resolution and fail to capture the often continuous nature of the underlying signal. Neural Fields (NFs) offer a powerful alternative by modeling data as continuous functions. While single-instance NFs have successfully been applied in medical contexts, extending them to large-scale medical datasets remains an open challenge. We therefore introduce MedFuncta, a unified framework for large-scale NF training on diverse medical signals. Building on Functa, our approach encodes data into a unified representation, namely a 1D latent vector, that modulates a shared, meta-learned NF, enabling generalization across a dataset. We revisit common design choices, introducing a non-constant frequency parameter ω in widely used SIREN activations, and establish a connection between this ω-schedule and layer-wise learning rates, relating our findings to recent work in theoretical learning dynamics. We additionally introduce a scalable meta-learning strategy for shared network learning that employs sparse supervision during training, thereby reducing memory consumption and computational overhead while maintaining competitive performance. Finally, we evaluate MedFuncta across a diverse range of medical datasets and show how to solve relevant downstream tasks on our neural data representation. To promote further research in this direction, we release our code, model weights and the first large-scale dataset - MedNF - containing > 500 k latent vectors for multi-instance medical NFs.

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://arxiv.org/pdf/2502.14401"

url_video: "https://www.youtube.com/watch?v=dNhdeJoVFto"

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

