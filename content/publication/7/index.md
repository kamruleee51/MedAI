---
title: "Associating Measles Vaccine Uptake Classification and Its Underlying Factors Using an Ensemble of Machine Learning Models"
authors:
- "Md Kamrul Hasan, Md Tasnim Jawad, Aishwariya Dutta, Md Abdul Awal, Md Akhtarul Islam, Mehedi Masud, Jehad F. Al-Amri "
#date: "2020-04-2"
doi: "https://doi.org/10.1109/ACCESS.2021.3108551"

#url_video: https://youtu.be/Knp4JIhH3Yo
  
# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-27"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access, Volume 9, 2021, 21080244, ISSN 2169-3536"
publication_short: "IEEE Access, Volume 9, 2021, 21080244, ISSN 2169-3536"


abstract: "Measles is one of the significant public health issues responsible for the high mortality
rate around the globe, especially for developing countries. Using nationally representative demographic
and health survey data, measles vaccine utilization has been classified, and its underlying factors are
identified through an ensemble Machine Learning (ML) approach. Firstly, missing values are imputed
employing various approaches, and then several feature selection techniques have been applied to identify the
crucial attributes for predicting measles vaccination. A grid search hyperparameter optimization technique
has been applied for tuning the critical hyperparameters of different ML models, such as Naive Bayes,
random forest, decision tree, XGboost, and lightgbm. The individual optimized ML model’s categorization
performance as all their ensembles have been reported utilizing our proposed BDHS dataset. Individually,
the optimized lightgbm provides the highest precision and AUC of 79.90 % and 77.80 %, respectively. This
result improved when the optimized lightgbm is ensembled with XGboost, providing the precision and AUC
of 84.60 % and 80.0 %, respectively. Our result reveals that the statistical median imputation technique with
the XGboost-based attribute selection method and the lightgbm classifier provides the best individual result.
The performance improved when the proposed weighted ensemble of the XGboost and lightgbm approach
was adapted with the same preprocessing and recommended for measles vaccine utilization. The significance
of our proposed approach is that it utilizes minimum attributes collected from the child and their family
members and yielded 80.0 % accuracy, making it easily explainable by caregivers and healthcare personnel.
Finally, our predictive model provides an early detection procedure to help national policymakers enforce
new policies with specific rules and regulations. The data and source codes that support the findings of this
study are available at https://github.com/kamruleee51/measles_vaccine_uptake."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Attribute selection
- Measles vaccine uptake classification
- Measles BDHS data
- Missing value imputation
- Weighted ensemble ML model
#featured: true
url_code: "https://github.com/kamruleee51/measles_vaccine_uptake"
 
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
