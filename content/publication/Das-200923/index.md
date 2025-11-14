---
title: "Diffusion Autoencoders: Toward a Meaningful and Decodable Representation"
authors:
- Konpat Preechakul
- Nattanat Chatthee
- Suttisak Wizadwongsa
- Supasorn Suwajanakorn

date: "2022-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Diffusion probabilistic models (DPMs) have achieved remarkable quality in image generation that rivals GANs'. But unlike GANs, DPMs use a set of latent variables that lack semantic meaning and cannot serve as a useful representation for other tasks. This paper explores the possibility of learning semantically meaningful representations from DPMs. We propose Diffusion Autoencoders (Diff-AE), which are DPMs that use an encoder to learn high-level semantics and a decoder to generate diverse images. We show that (i) the encoder can deterministically map any input image into a 512-dimensional semantic encoding, (ii) the decoder can condition on this encoding to generate diverse high-quality images sharing the same semantics, and (iii) the resulting semantic representation is useful for downstream tasks, such as real image manipulation and interpolation. Our approach is simple: we train an encoder that learns to reverse the forward diffusion process to extract a semantic representation from an image, and a decoder that learns to reconstruct the image based on this extracted representation. We show that both can be trained jointly by optimizing a simple reconstruction loss on ImageNet. Our code and models are available at https://github.com/phizaz/diffae."

# Summary. An optional shortened abstract.
summary: ""

tags: []
featured: false

url_pdf: "https://openaccess.thecvf.com/content/CVPR2022/papers/Preechakul_Diffusion_Autoencoders_Toward_a_Meaningful_and_Decodable_Representation_CVPR_2022_paper.pdf"

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

