---
title: "Hierarchical Reconstruction of 7T-like Images from 3T MRI Using Multi-level CCA and Group Sparsity"
authors:
- Khosro Bahrami
- Feng Shi
- Xiaopeng Zong
- Hae Won Shin
- Hongyu An
- Dinggang Shen
date: "2015-11-20T00:00:00Z"
doi: "10.1007/978-3-319-24571-3_79"

# Schedule page publish date (NOT publication's date).
publishDate: "2015-11-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Medical Image Computing and Computer-Assisted Intervention -- MICCAI 2015"
publication_short: "MICCAI 2015"

abstract: "Advancements in 7T MR imaging bring higher spatial resolution and clearer tissue contrast, in comparison to the conventional 3T and 1.5T MR scanners. However, 7T MRI scanners are less accessible at the current stage due to higher costs. Through analyzing the appearances of 7T images, we could improve both the resolution and quality of 3T images by properly mapping them to 7T-like images; thus, promoting more accurate post-processing tasks, such as segmentation. To achieve this method based on an unique dataset acquired both 3T and 7T images from same subjects, we propose novel multi-level Canonical Correlation Analysis (CCA) method and group sparsity as a hierarchical framework to reconstruct 7T-like MRI from 3T MRI. First, the input 3T MR image is partitioned into a set of overlapping patches. For each patch, the local coupled 3T and 7T dictionaries are constructed by extracting the patches from a neighboring region from all aligned 3T and 7T images in the training set. In the training phase, we have both 3T and 7T MR images scanned from each training subject. Then, these two patch sets are mapped to the same space using multi-level CCA. Next, each input 3T MRI patch is sparsely represented by the 3T dictionary and then the obtained sparse coefficients are utilized to reconstruct the 7T patch with the corresponding 7T dictionary. Group sparsity is further utilized to maintain the consistency between neighboring patches. Such reconstruction is performed hierarchically with adaptive patch size. The experiments were performed on 10 subjects who had both 3T and 7T MR images. Experimental results demonstrate that our proposed method is capable of recovering rich structural details and outperforms other methods, including the sparse representation method and CCA method."

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://link.springer.com/chapter/10.1007/978-3-319-24571-3_79"

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

