---
title: "Multi-scale, data-driven and anatomically constrained deep learning image registration for adult and fetal echocardiography"
authors:
- "Md. Kamrul Hasan, Haobo Zhu, Guang Yang, Choon Hwai Yap"
#date: "2023-09-2"
doi: "https://arxiv.org/abs/2309.00831"

url_video: https://www.youtube.com/watch?v=eGUU-rqWznY&t=4s&loop=0
 

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-02"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "ArXiv"
publication_short: "ArXiv"

abstract: "Temporal echocardiography image registration is important for cardiac motion estimation, myocardial strain assessments, and stroke volume quantifications. Deep learning image registration is a promising way to achieve consistent and accurate registration results with low computational time. We propose that a greater focus on the warped image's anatomic plausibility and image texture can support robust results and show that it has sufficient robustness to be applied to both fetal and adult echocardiography. Our proposed framework includes (1) an anatomic shape-encoded loss to preserve physiological myocardial and left ventricular anatomical topologies, (2) a data-driven loss to preserve good texture features, and (3) a multi-scale training of a data-driven and anatomically constrained algorithm to improve accuracy. Our experiments demonstrate a strong correlation between the shape-encoded loss and good anatomical topology and between the data-driven loss and image textures. They improve different aspects of registration results in a non-overlapping way. We demonstrate that these methods can successfully register both adult and fetal echocardiography using the public CAMUS adult dataset and our fetal dataset, despite the inherent differences between adult and fetal echocardiography. Our approach also outperforms traditional non-DL gold standard registration approaches, including optical flow and Elastix, and could be translated into more accurate and precise clinical quantification of cardiac ejection fraction, demonstrating potential for clinical utility."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Echocardiography registration
- Deep learning image registration
- Adult and fetal echocardiography
- Anatomical and data-driven constraints
featured: true
url_code: "https://github.com/kamruleee51/ddc-ac-dlir"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Proposed data-driven and anatomically constrained DLIR'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []


---
