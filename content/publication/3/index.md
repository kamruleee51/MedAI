---
title: "Diabetes Prediction Using Ensembling of Different Machine Learning Classifiers"
authors:
- "Md Kamrul Hasan, Md Aahraful Alam, Dola Das, Eklas Hossian, Mahmudul Hasan"
#date: "2020-04-2"
doi: "https://doi.org/10.1109/ACCESS.2020.2989857"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-23"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access, Volume 8, 2020, 19581985, ISSN 2169-3536"
publication_short: "IEEE Access, Volume 8, 2020, 19581985, ISSN 2169-3536"

abstract: "Diabetes, also known as chronic illness, is a group of metabolic diseases due to a high level of sugar in the blood over a long period.
The risk factor and severity of diabetes can be reduced significantly if the precise early prediction is possible. 
The robust and accurate prediction of diabetes is highly challenging due to the limited number of labeled data and also the presence of outliers
(or missing values) in the diabetes datasets. In this literature, we are proposing a robust framework for diabetes prediction where the outlier 
rejection, filling the missing values, data standardization, feature selection, K-fold cross-validation, and different Machine Learning (ML) 
classifiers (k-nearest Neighbour, Decision Trees, Random Forest, AdaBoost, Naive Bayes, and XGBoost) and Multilayer Perceptron (MLP) were employed. 
The weighted ensembling of different ML models is also proposed, in this literature, to improve the prediction of diabetes where the weights are 
estimated from the corresponding Area Under ROC Curve (AUC) of the ML model. AUC is chosen as the performance metric, which is then maximized during 
hyperparameter tuning using the grid search technique. All the experiments, in this literature, were conducted under the same experimental conditions 
using the Pima Indian Diabetes Dataset. From all the extensive experiments, our proposed ensembling classifier is the best performing classifier with 
the sensitivity, specificity, false omission rate, diagnostic odds ratio, and AUC as 0.789, 0.934, 0.092, 66.234, and 0.950 respectively which outperforms 
the state-of-the-art results by 2.00 % in AUC. Our proposed framework for the diabetes prediction outperforms the other methods discussed in the article. 
It can also provide better results on the same dataset which can lead to better performance in diabetes prediction. Our source code for diabetes 
prediction is made publicly available."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Diabetes prediction
- Ensembling classifier
- Machine learning
- Multilayer perceptron
- Missing values and outliers
- Pima Indian Diabetic dataset
featured: true
url_code: https://github.com/kamruleee51/Diabetes-Prediction-Using-ML-Classifiers

 
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Proposed Ensembling of Different Machine Learning Classifiers'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []


---
