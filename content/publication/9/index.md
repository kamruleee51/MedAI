---
title: "Multi-Class Probabilistic Atlas-Based Whole Heart Segmentation Method in Cardiac CT and MRI"
authors:
- "Tarun Kanti Ghosh, Md Kamrul Hasan, Shidhartho Roy, Md Ashraful Alam, Eklas Hossian, Mohiuddin Ahmad"
#date: "2020-04-2"
doi: "https://doi.org/10.1109/ACCESS.2021.3077006"

#url_video: https://youtu.be/Knp4JIhH3Yo
  
# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-03"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access, Volume 9, 2021, 20986072, ISSN 2169-3536"
publication_short: "IEEE Access, Volume 9, 2021, 20986072, ISSN 2169-3536"


abstract: " Accurate and robust whole heart substructure segmentation is crucial in developing clinical applications, 
such as computer-aided diagnosis and computer-aided surgery. However, the segmentation of different heart substructures 
is challenging because of inadequate edge or boundary information, the complexity of the background and texture, and the 
diversity in different substructures’ sizes and shapes. This article proposes a framework for multi-class whole heart 
segmentation employing non-rigid registration-based probabilistic atlas incorporating the Bayesian framework. 
We also propose a non-rigid registration pipeline utilizing a multi-resolution strategy for obtaining the highest 
attainable mutual information between the moving and fixed images. We further incorporate non-rigid registration into 
the expectation-maximization algorithm and implement different deep convolutional neural network-based encoder-decoder 
networks for ablation studies. All the extensive experiments are conducted utilizing the publicly available dataset for 
the whole heart segmentation containing 20 MRI and 20 CT cardiac images. The proposed approach exhibits an encouraging achievement, 
yielding a mean volume overlapping error of 14.5 % for CT scans exceeding the state-of-the-art results by a margin of 1.3 % in terms 
of the same metric. As the proposed approach provides better results to delineate the different substructures of the heart, it can be 
a medical diagnostic aiding tool for helping experts with quicker and more accurate results. "

# Summary. An optional shortened abstract.
summary: ''

tags:
- Image segmentation
- CNNs
- Deep learning
- Medical image analysis
- Image registration
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
