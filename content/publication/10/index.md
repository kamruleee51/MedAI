---
title: "COVID-19 identification from volumetric chest CT scans using a progressively resized 3D-CNN incorporating segmentation, augmentation, and class-rebalancing"
authors:
- "Md Kamrul Hasan, Md Tasnim Jawada, Kazi Nasim Imtiaz Hasanb, Sajal Basak Partha, Md Masum Al Masba, Shumit Saha, Mohammad Ali Moni"
#date: "2020-04-2"
doi: "https://doi.org/10.1016/j.imu.2021.100709"

#url_video: https://youtu.be/Knp4JIhH3Yo
  
# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-18"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Informatics in Medicine Unlocked, Volume 26, 2021, 100709"
publication_short: "Informatics in Medicine Unlocked, Volume 26, 2021, 100709"


abstract: " The novel COVID-19 is a global pandemic disease overgrowing worldwide. 
Computer-aided screening tools with greater sensitivity are imperative for disease diagnosis and prognosis as early as possible. 
It also can be a helpful tool in triage for testing and clinical supervision of COVID-19 patients. However, designing such an automated 
tool from non-invasive radiographic images is challenging as many manually annotated datasets are not publicly available yet, which is the 
essential core requirement of supervised learning schemes. This article proposes a 3D Convolutional Neural Network (CNN)-based classification 
approach considering both the inter-and intra-slice spatial voxel information. The proposed system is trained end-to-end on the 3D patches 
from the whole volumetric Computed Tomography (CT) images to enlarge the number of training samples, performing the ablation studies on patch 
size determination. We integrate progressive resizing, segmentation, augmentations, and class-rebalancing into our 3D network. The segmentation 
is a critical prerequisite step for COVID-19 diagnosis enabling the classifier to learn prominent lung features while excluding the outer 
lung regions of the CT scans. We evaluate all the extensive experiments on a publicly available dataset named MosMed, having binary- and 
multi-class chest CT image partitions. Our experimental results are very encouraging, yielding areas under the Receiver Operating Characteristics (ROC) curve of 
0.914±0.049 and 0.893±0.035 for the binary- and multi-class tasks, respectively, applying 5-fold cross-validations. Our method’s promising 
results delegate it as a favorable aiding tool for clinical practitioners and radiologists to assess COVID-19. "

# Summary. An optional shortened abstract.
summary: ''

tags:
- COVID-19
- 3D convolutional neural network
- Volumetric chest CT scans
- 3D patches
- Progressive resizing
#featured: true
url_code: ""
 

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
