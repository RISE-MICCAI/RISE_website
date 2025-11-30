---
title: "Scaling Artificial Intelligence for Multi-Tumor Early Detection with More Reports, Fewer Masks"
authors:
- Pedro R. A. S. Bassi
- Xinze Zhou
- Wenxuan Li
- Szymon Płotka
- Jieneng Chen
- Qi Chen
- Zheren Zhu
- Jakub Prządo
- Ibrahim E. Hamacı
- Sezgin Er
- Yuhan Wang
- Ashwin Kumar
- Bjoern Menze
- Jarosław B. Ćwikła
- Yuyin Zhou
- Akshay S. Chaudhari
- Curtis P. Langlotz
- Sergio Decherchi
- Andrea Cavalli
- Kang Wang
- Yang Yang
- Alan L. Yuille
- Zongwei Zhou
date: "2025-12-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "MICCAI 2025"
publication_short: ""

abstract: |
  **Speaker:** Pedro Bassi

  Early tumor detection saves lives. Each year, more than 300 million computed tomography (CT) scans are performed worldwide, offering a vast opportunity for cancer screening. However, detecting small or early-stage tumors on these CT scans is challenging, even for experts. Artificial intelligence (AI) segmentation models can assist by highlighting suspicious regions, but training such models typically requires a large number of tumor masks (detailed, voxel-wise outlines of tumors drawn by radiologists). Drawing these masks is costly, and public datasets contain few masks, covering tumors in few organs. In contrast, nearly every CT scan in clinical practice is already accompanied by radiology reports describing the tumor's size, number, location, and appearance. We introduce R-Super, which trains AI to segment tumors that match tumor descriptions in radiology reports. R-Super uses reports to substitute or supplement masks in segmentation training. First, we trained R-Super to segment kidney and pancreas tumors with 6,718 CT-Report pairs plus different numbers of CT-Mask pairs. With few (50), medium (344) or many (1.7K) CT-Mask pairs, R-Super substantially outperformed previous methods. In comparison to usual training with just CT-Mask pairs, R-Super boosted F1-Score and DSC up to 16% and 11%. Next, we trained R-Super on 101,654 CT-Report pairs, enabling the segmentation of tumors in the spleen, gallbladder, prostate, bladder, uterus, and esophagus—tumors for which no public masks or AI models existed. By reducing the need for tumor masks, this study offers a scalable and accessible path toward early detection across diverse tumor types.

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://arxiv.org/pdf/2510.14803"

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

