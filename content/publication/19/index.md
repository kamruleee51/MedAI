---
title: "Early Prediction of Diabetes Using an Ensemble of Machine Learning Models"
authors:
- "Aishwariya Dutta, Md Hasan, Mohiuddin Ahmad, Md Awal, Md Islam, Mehedi Masud, Hossam Meshref"
#date: "2020-04-2"
doi: "https://doi.org/10.3390/ijerph191912378"

#url_video: https://youtu.be/Knp4JIhH3Yo
  
# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Multidisciplinary Digital Publishing Institute"
publication_short: "International Journal of Environmental Research and Public Health"


abstract: "Diabetes is one of the most rapidly spreading diseases in the world, resulting in an array of significant complications, including cardiovascular disease, kidney failure, diabetic retinopathy, and neuropathy, among others, which contribute to an increase in morbidity and mortality rate. If diabetes is diagnosed at an early stage, its severity and underlying risk factors can be significantly reduced. However, there is a shortage of labeled data and the occurrence of outliers or data missingness in clinical datasets that are reliable and effective for diabetes prediction, making it a challenging endeavor. Therefore, we introduce a newly labeled diabetes dataset from a South Asian nation (Bangladesh). In addition, we suggest an automated classification pipeline that includes a weighted ensemble of machine learning (ML) classifiers: Naive Bayes (NB), Random Forest (RF), Decision Tree (DT), XGBoost (XGB), and LightGBM (LGB). Grid search hyperparameter optimization is employed to tune the critical hyperparameters of these ML models. Furthermore, missing value imputation, feature selection, and K-fold cross-validation are included in the framework design. A statistical analysis of variance (ANOVA) test reveals that the performance of diabetes prediction significantly improves when the proposed weighted ensemble (DT + RF + XGB + LGB) is executed with the introduced preprocessing, with the highest accuracy of 0.735 and an area under the ROC curve (AUC) of 0.832. In conjunction with the suggested ensemble model, our statistical imputation and RF-based feature selection techniques produced the best results for early diabetes prediction. Moreover, the presented new dataset will contribute to developing and implementing robust ML models for diabetes prediction utilizing population-level data."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Artificial intelligence
- Diabetes prediction
- Ensemble ML classifier
- Filling missing value
- Outlier rejection
- South Asian diabetes dataset
#featured: true
url_code: "https://github.com/kamruleee51/Diabetes-classification-dataset"
  
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
