---
title: "Improved 3D Whole Heart Geometry from Sparse CMR Slices"
authors:
- Yiyang Xu
- Hao Xu
- Matthew Sinclair
- Esther Puyol-Antón
- Steven A Niederer
- Amedeo Chiribiri
- Steven E Williams
- Michelle C Williams
- Alistair A Young
date: "2024-11-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: |
  **Speaker:** Yiyang Xu

  Cardiac magnetic resonance (CMR) imaging and computed tomography (CT) are two common non-invasive imaging methods for assessing patients with cardiovascular disease. CMR typically acquires multiple sparse 2D slices, with unavoidable respiratory motion artefacts between slices, whereas CT acquires isotropic dense data but uses ionising radiation. In this study, we explore the combination of Slice Shifting Algorithm (SSA), Spatial Transformer Network (STN), and Label Transformer Network (LTN) to: 1) correct respiratory motion between segmented slices, and 2) transform sparse segmentation data into dense segmentation. All combinations were validated using synthetic motion-corrupted CMR slice segmentation generated from CT in 1699 cases, where the dense CT serves as the ground truth. In 199 testing cases, SSA-LTN achieved the best results for Dice score and Huasdorff distance (94.0% and 4.7 mm respectively, average over 5 labels) but gave topological errors in 8 cases. STN was effective as a plug-in tool for correcting all topological errors with minimal impact on overall performance (93.5% and 5.0 mm respectively). SSA also proves to be a valuable plug-in tool, enhancing performance over both STN-based and LTN-based models. The code for these different combinations is available at https://github.com/XESchong/STACOM2024.

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://arxiv.org/pdf/2408.07532"

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

