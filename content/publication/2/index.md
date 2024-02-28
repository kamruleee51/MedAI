---
title: "DSNet: Automatic dermoscopic skin lesion segmentation"
authors:
- "Md Kamrul Hasan, Lavsen Dahal, Prasad N. Samarakoon, Fakrul Islam Tushar, Robert Martí"
date: "2020-03-27"
doi: "10.1016/j.compbiomed.2020.103738"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-02"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers in Biology and Medicine, Volume 120, 2020, 103738, ISSN 0010-4825"
publication_short: "Computers in Biology and Medicine, Volume 120, 2020, 103738, ISSN 0010-4825"

abstract: "Automatic segmentation of skin lesions is considered a crucial step in Computer-aided Diagnosis (CAD) systems for melanoma detection.
Despite its significance, skin lesion segmentation remains an unsolved challenge due to their variability in color, texture, and shape and 
indistinguishable boundaries. Through this study, we present a new and automatic semantic segmentation network for robust skin lesion segmentation named Dermoscopic Skin Network (DSNet). In order to reduce the number of parameters to make the network lightweight, we used a depth-wise separable convolution instead of standard convolution to project the learned discriminating features onto the pixel space at different stages of the encoder. We also implemented a U-Net and a Fully Convolutional Network (FCN8s) to compare against the proposed DSNet. We evaluate our proposed model on two publicly available datasets, ISIC-2017 and PH2. The obtained mean Intersection over Union (mIoU) is 77.5% and 87.0%, respectively, for ISIC-2017 and PH2 datasets, which outperformed the ISIC-2017 challenge winner by 1.0% concerning mIoU. Our proposed network outperformed U-Net and FCN8s by 3.6% and 6.8% concerning mIoU on the ISIC-2017 dataset, respectively. Our network for skin lesion segmentation outperforms the other methods discussed in the article. It can provide better-segmented masks on two different test datasets, leading to better performance in melanoma detection. Our trained model, source code, and predicted masks are made publicly available."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Skin lesion segmentation
- Computer-aided diagnosis
- Melanoma detection
- Deep learning
- Fully convolutional network
- UNet
- ISIC-2017
- PH2
featured: true
url_code: https://github.com/kamruleee51/Skin-Lesion-Segmentation-Using-Proposed-DSNet
url_video: https://www.youtube.com/watch?v=m3u58LN9lns&loop=0
 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Qualitative results of DSNet'
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
# slides: example
---
