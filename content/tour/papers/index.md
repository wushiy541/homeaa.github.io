---
title: "A low-rank support tensor machine for multi-classification[J]"
authors:
- Jinrui Yang
- Shuangyi Fan
- Libo Zhang* 
- Dun Liu*. 
date: "2025-06-04T00:00:00Z"
doi: "10.1016/j.ins.2024.121398"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Information Sciences"
publication_short: ""

volume: "688"  # 卷号
issue: ""    # 期号
pages: "121398"  # 页码范围（可选

abstract: In recent decades, there has been an increasing demand for effectively handling high-dimensional multi-channel tensor data. Due to the inability to utilize internal structural information, Support Vector Machine (SVM) and its variations struggle to classify flattened tensor data, consequently resulting in the ‘curse of dimensionality’ issue. Furthermore, most of these methods can not directly apply to multiclass datasets. To overcome these challenges, we have developed a novel classification method called Multiclass Low-Rank Support Tensor Machine (MLRSTM). Our method is inspired by the well-established low-rank tensor hypothesis, which suggests a correlation between each channel of the feature tensor. Specifically, MLRSTM adopts the hinge loss function and introduces a convex approximation of tensor rank, the order-d Tensor Nuclear Norm (order-d TNN), in the regularization term. By leveraging the order-d TNN, MLRSTM effectively exploits the inherent structural information in tensor data to enhance generalization performance and avoid the curse of dimensionality. Moreover, we develop the Alternating Direction Method of Multipliers (ADMM) algorithm to optimize the convex problem inherent in training MLRSTM. Finally, comprehensive experiments validate the excellent performance of MLRSTM in tensor multi-classification tasks, showcasing its potential and efficacy in handling high-dimensional multi-channel tensor data.



featured: false

links:
- name: Custom Link
  url: https://doi.org/10.1016/j.ins.2024.121398
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---