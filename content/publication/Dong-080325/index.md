---
title: "Deep Learning for Detecting Progressive Changes in Alzheimer’s Disease"
authors:
- Mengjin Dong
# author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-03-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-08T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Imaging Neuroscience"
publication_short: ""

abstract: Longitudinal assessment of brain atrophy, particularly in the hippocampus, is a well-studied biomarker for neurodegenerative diseases, such as Alzheimer’s disease (AD). Estimating brain progression patterns can be applied to understanding the therapeutic effects of amyloid-clearing drugs in research and detecting the earliest sign of accelerated atrophy in clinical settings. However, most state-of-the-art measurements calculate changes directly by segmentation and/or deformable registration of MRI images, and may misreport head motion or MRI artifacts as neurodegeneration, impacting their accuracy. In our previous study, we developed a deep learning method DeepAtrophy that uses a convolutional neural network to quantify differences between longitudinal MRI scan pairs that are associated with time. DeepAtrophy has high accuracy in inferring temporal information from longitudinal MRI scans, such as temporal order or relative interscan interval. DeepAtrophy also provides an overall atrophy score that was shown to perform well as a potential biomarker of disease progression and treatment efficacy. However, DeepAtrophy is not interpretable, and it is unclear what changes in the MRI contribute to progression measurements. In this paper, we propose Regional Deep Atrophy (RDA), which combines the temporal inference approach from DeepAtrophy with a deformable registration neural network and attention mechanism that highlights regions in the MRI image where longitudinal changes are contributing to temporal inference. RDA has similar prediction accuracy as DeepAtrophy, but its additional interpretability makes it more acceptable for use in clinical settings, and may lead to more sensitive biomarkers for disease monitoring and progression understanding in preclinical AD.

# Summary. An optional shortened abstract.
summary: This paper introduces Regional Deep Atrophy (RDA), an interpretable deep learning method that combines temporal inference from longitudinal MRI scans with an attention-based deformable registration network to highlight brain regions contributing to atrophy. While maintaining the accuracy of the earlier DeepAtrophy model, RDA improves clinical usability by offering insight into regional brain changes, potentially enhancing early detection and monitoring of Alzheimer’s disease progression and treatment effects.

tags:
#- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://direct.mit.edu/imag/article-pdf/doi/10.1162/imag_a_00294/2470593/imag_a_00294.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

