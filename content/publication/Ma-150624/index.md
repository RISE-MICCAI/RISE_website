---
title: "Foundation Ark: Accruing and Reusing Knowledge for Superior and Robust Performance"
authors:
- DongAo Ma
- Jiaxuan Pang
- Michael B. Gotway
- Jianming Liang
date: "2023-10-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Deep learning nowadays offers expert-level and sometimes even super-expert-level performance, but achieving such performance demands massive annotated data for training (e.g., Google's proprietary CXR Foundation Model (CXR-FM) was trained on 821,544 labeled and mostly private chest X-rays (CXRs)). Numerous datasets are publicly available in medical imaging but individually small and heterogeneous in expert labels. We envision a powerful and robust foundation model that can be trained by aggregating numerous small public datasets. To realize this vision, we have developed Ark, a framework that accrues and reuses knowledge from heterogeneous expert annotations in various datasets. As a proof of concept, we have trained two Ark models on 335,484 and 704,363 CXRs, respectively, by merging several datasets including ChestX-ray14, CheXpert, MIMIC-II, and VinDr-CXR, evaluated them on a wide range of imaging tasks covering both classification and segmentation via fine-tuning, linear-probing, and gender-bias analysis, and demonstrated our Ark's superior and robust performance over the SOTA fully/self-supervised baselines and Google's proprietary CXR-FM. This enhanced performance is attributed to our simple yet powerful observation that aggregating numerous public datasets diversifies patient populations and accrues knowledge from diverse experts, yielding unprecedented performance yet saving annotation cost. With all codes and pretrained models released at GitHub.com/JLiangLab/Ark, we hope that Ark exerts an important impact on open science, as accruing and reusing knowledge from expert annotations in public datasets can potentially surpass the performance of proprietary models trained on unusually large data, inspiring many more researchers worldwide to share codes and datasets to build open foundation models, accelerate open science, and democratize deep learning for medical imaging."

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://arxiv.org/pdf/2310.09507"

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

