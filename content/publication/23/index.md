---
title: "Ensemble of Convolutional Neural Networks to diagnose Acute Lymphoblastic Leukemia from microscopic images"
authors:
- "Chayan Mondal, Md Kamrul Hasan, Mohiuddin Ahmad, Md Abdul Awal, Md Tasnim Jawad, Aishwariya Dutta, Md Rabiul Islam, Mohammad Ali Moni"
#date: "2020-04-2"
doi: "https://doi.org/10.1016/j.imu.2021.100794"

#url_video: https://youtu.be/Knp4JIhH3Yo
  
# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Elsevier"
publication_short: "Informatics in Medicine Unlocked"


abstract: "Acute Lymphoblastic Leukemia (ALL) is a blood cell cancer characterized by the presence of excess immature lymphocytes., Even though automation in ALL prognosis is essential for cancer diagnosis, it remains a challenge due to the morphological correlation between malignant and normal cells. The traditional ALL classification strategy demands that experienced pathologists read cell images carefully, which is arduous, time-consuming, and often hampered by interobserver variation. This article has automated the ALL recognition task by employing deep Convolutional Neural Networks (CNNs). The weighted ensemble of deep CNNs is explored to recommend a better ALL cell classifier. The weights are estimated from ensemble candidates’ corresponding metrics, such as F1-score, area under the curve (AUC), and kappa values. Various data augmentations and pre-processing are incorporated to achieve a better generalization of the network. Our proposed model was trained and evaluated utilizing the C-NMC-2019 ALL dataset. The proposed weighted ensemble model has outputted a weighted F1-score of 89.7%, a balanced accuracy of 88.3%, and an AUC of 0.948 in the preliminary test set. The qualitative results displaying the gradient class activation maps confirm that the introduced model has a concentrated learned region. In contrast, the ensemble candidate models, such as Xception, VGG-16, DenseNet-121, MobileNet, and InceptionResNet-V2, separately exhibit coarse and scatter learned areas in most cases. Since the proposed ensemble yields a better result for the aimed task, it can support clinical decisions to detect ALL patients in an early stage."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Deep learning 
- CNNs
- AI in medical imaging 
- Medical image analysis 
- Image classification 
#featured: true
# url_code: "https://github.com/kamruleee51/Automatic-Mass-Classification-in-Breast"
  
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
