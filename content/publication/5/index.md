---
title: "Dermo-DOCTOR: A framework for concurrent skin lesion detection and recognition using a deep convolutional neural network with end-to-end dual encoders"
authors:
- "Md Kamrul Hasan, Shidhartho Roy, Chayan Mondal, Md Ashraful Alam, Md Toufick E Elahi, Aishwariya Dutta, S. M. Taslim Uddin Raju, Md Tasnim Jawad, Mohiuddin Ahmad"
#date: "2020-04-2"
doi: "https://doi.org/10.1016/j.bspc.2021.102661"


# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-15"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Biomedical Signal Processing and Control, Volume 68, 2021, 102661"
publication_short: "Biomedical Signal Processing and Control, Volume 68, 2021, 102661"

abstract: "This article proposes an end-to-end deep CNN-based framework for simultaneous detection and recognition of skin lesions, Dermo-DOCTOR, consisting of two encoders. The feature maps from two encoders are fused channel-wise, called Fused Feature Map (FFM). The FFM is utilized for decoding in the detection sub-network, concatenating each stage of two encoders’ outputs with corresponding decoder layers to retrieve the lost spatial information due to pooling in the encoders. For the recognition sub-network, the outputs of three fully connected layers, utilizing feature maps of two encoders and FFM, are aggregated to obtain a final lesion class. We train and evaluate the proposed Dermo-Doctor utilizing two publicly available benchmark datasets, such as ISIC-2016 and ISIC-2017.
The achieved segmentation results exhibit mean intersection over unions of 85.0% and 80.0%, respectively, for ISIC-2016 and ISIC-2017 test datasets. The proposed Dermo-DOCTOR also demonstrates praiseworthy success in lesion recognition, providing the areas under the receiver operating characteristic curves of 0.98 and 0.91 for those two datasets, respectively. The experimental results show that the proposed Dermo-DOCTOR outperforms the alternative methods mentioned in the literature for skin lesion detection and recognition. As the Dermo-DOCTOR provides better results on two different test datasets, it can be an auspicious computer-aided assistive tool for dermatologists even with limited training data."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Deep learning
- CNNs
- AI in medical imaging
- Medical image analysis
- Image segmentation
- Image classification
featured: true
url_video: "https://www.youtube.com/watch?v=6Rs-jifzlwM&loop=0"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Workflow of the proposed Dermo-DOCTOR'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []


---
