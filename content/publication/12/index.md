---
title: "Automatic Mass Classification in Breast Using Transfer Learning of Deep Convolutional Neural Network and Support Vector Machine"
authors:
- "Aishwariya Dutta, Md Kamrul Hasan, Mohiuddin Ahmad"
#date: "2020-04-2"
doi: "https://doi.org/10.1109/TENSYMP50017.2020.9230708"

#url_video: https://youtu.be/Knp4JIhH3Yo
  
# Schedule page publish date (NOT publication's date).
publishDate: "2021"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Region 10 Symposium (TENSYMP), 20115574"
publication_short: "IEEE Region 10 Symposium (TENSYMP), 20115574"


abstract: "Mammography is the most widely used gold standard for screening breast cancer, where mass classification is a prominent step. 
Classification of mass in the breast is, however, an arduous problem as they usually have large variations in terms of shape, size, boundary, 
and texture. In this study, the process of mass classification is automated with the use of transfer learning of Deep Convolutional Neural 
Networks (DCNN) to extract features, the bagged decision tree for feature selection, and finally a Support Vector Machine (SVM) 
classifier for classifying the mass and non-mass tissue. Area Under ROC Curve (AUC) is chosen as the performance metric, which is 
then maximized for hyper-parameter tuning using a grid search. All experiments, in this paper, were conducted using the INbreast dataset. 
The best obtained AUC from the experimental results is O.994±0.003. Our results conclude that high-level distinctive features can be extracted 
from Mammograms by using the pre-trained DCNN, which can be used with the SVM classifier to robustly distinguish between the mass and non-mass
 presence in the breast."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Mammography
- Deep Convolutional Neural Networks
- Transfer Learning
- Support Vector Machine
- INbreast dataset

#featured: true
url_code: "https://github.com/kamruleee51/Automatic-Mass-Classification-in-Breast"
  
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
