---
title: "DermoExpert: Skin lesion classification using a hybrid convolutional neural network through segmentation, transfer learning, and augmentation"
authors:
- "Md Kamrul Hasan, Md Toufick E Elahi, Md Ashraful Alam, Md Tasnim Jawad, Robert Martí"
#
#date: "2020-04-2"
doi: "https://doi.org/10.1016/j.imu.2021.100819"

#url_video: https://youtu.be/Knp4JIhH3Yo
  
# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-12"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Informatics in Medicine Unlocked"
publication_short: "Informatics in Medicine Unlocked"


abstract: "Background and Objective: Although automated Skin Lesion Classification (SLC) is a crucial integral step
in computer-aided diagnosis, it remains challenging due to variability in textures, colors, indistinguishable
boundaries, and shapes.
Methods: This article proposes an automated dermoscopic SLC framework named Dermoscopic Expert (Dermo-
Expert). It combines the pre-processing and hybrid Convolutional Neural Network (hybrid-CNN). The proposed
hybrid-CNN has three distinct feature extractor modules, which are fused to achieve better-depth feature
maps of the lesion. Those single and fused feature maps are classified using different fully connected layers,
then ensembled to predict a lesion class. In the proposed pre-processing, we apply lesion segmentation,
augmentation (geometry- and intensity-based), and class rebalancing (penalizing the majority class’s loss
and merging additional images to the minority classes). Moreover, we leverage transfer learning from the
pre-trained models. Finally, we deploy the weights of our DermoExpert to a possible web application.
Results: We evaluate our DermoExpert on the ISIC-2016, ISIC-2017, and ISIC-2018 datasets, where the
DermoExpert has achieved the area under the receiver operating characteristic curve (AUC) of 0.96, 0.95, and
0.97, respectively. The experimental results improve the state-of-the-art by the margins of 10.0% and 2.0%,
respectively, for the ISIC-2016 and ISIC-2017 datasets in terms of AUC. The DermoExpert also outperforms by
3.0% for the ISIC-2018 dataset concerning a balanced accuracy.
Conclusion: Since DermoExpert provides better classification outcomes on three different datasets, leading to
a better recognition tool to assist dermatologists. Our source code and segmented masks for the ISIC-2018
dataset will be available as a public benchmark for future improvements."

# Summary. An optional shortened abstract.
summary: ''
#
tags:
- Deep learning 
- CNNs 
- AI in medical imaging
- Medical image analysis
- Image segmentation
- Image classification
#featured: true
url_code: "https://github.com/kamruleee51/Web-App-of-Skin-Lesion-Classification"
  
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Proposed framework '
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---
