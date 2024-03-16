---
title: "Grasp-and-Lift Detection from EEG Signal Using Convolutional Neural Network"
authors:
- "Md Kamrul Hasan, Sifat Redwan Wahid, Faria Rahman, Shanjida Khan Maliha, Sauda Binte Rahman"
#date: "2020-04-2"
doi: "https://doi.org/10.1109/ICAEEE54957.2022.9836375"

#url_video: https://youtu.be/Knp4JIhH3Yo
  
# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-24"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE"
publication_short: "2022 International Conference on Advancement in Electrical and Electronic Engineering (ICAEEE)"


abstract: "People undergoing neuromuscular dysfunctions and amputated limbs require automatic prosthetic appliances. In developing such prostheses, the precise detection of brain motor actions is imperative for the Grasp-and-Lift (GAL) tasks. Because of the low-cost and non-invasive essence of Electroencephalogra-phy (EEG), it is widely preferred for detecting motor actions while controlling prosthetic tools. This article has automated the hand movement activity viz GAL detection method from the 32-channel EEG signals. The proposed pipeline essentially combines preprocessing and end-to-end detection steps, eliminating the requirement of hand-crafted feature engineering. Preprocessing action consists of raw signal denoising, using either Discrete Wavelet Transform (DWT) or highpass or bandpass filtering and data standardization. The detection step consists of Convolutional Neural Network (CNN)- or Long Short Term Memory (LSTM)-based model. All the investigations utilize the publicly available WAY-EEG-GAL dataset, having six different GAL events. The best experiment reveals that the proposed framework achieves an average area under the ROC curve of 0.944, employing the DWT-based denoising filter, data standardization, and CNN-based detection model. The obtained outcome designates an excellent achievement of the introduced method in detecting GAL events from the EEG signals, turning it applicable to prosthetic appliances, brain-computer interfaces, robotic arms, etc."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Data preprocessing 
- Machine learning 
- Data Science 
- Feature engineering 
- CNNs 
- Biomedical signal processing  
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
