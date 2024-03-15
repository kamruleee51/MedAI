---
title: "DRNet: Segmentation and localization of optic disc and Fovea from diabetic retinopathy image"
authors:
- "Md. Kamrul Hasan, Md Ashraful Alam, Md Toufick E Elahi, Shidhartho Roy, Robert Martí"
#date: "2020-04-2"
doi: "https://doi.org/10.1016/j.artmed.2020.102001"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-12-06"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Artificial Intelligence in Medicine, Volume 111, 2021, 102001"
publication_short: "Artificial Intelligence in Medicine, Volume 111, 2021, 102001"

abstract: "This article introduces a novel end-to-end encoder-decoder network, DRNet, explicitly designed for the segmentation and localization of OD and Fovea centers. In our DRNet, we propose a skip connection, named residual skip connection, to compensate for the spatial information lost due to pooling in the encoder. Unlike the earlier skip connection in the UNet, the proposed skip connection does not directly concatenate low-level feature maps from the encoder's beginning layers with the corresponding same-scale decoder. We validate DRNet using different publicly available datasets, such as IDRiD, RIMONE, DRISHTI-GS, and DRIVE for OD segmentation; IDRiD and HRF for OD center localization; and IDRiD for Fovea center localization. The proposed DRNet, for OD segmentation, achieves mean Intersection over Union (mIoU) of 0.845, 0.901, 0.933, and 0.920 for IDRiD, RIMONE, DRISHTI-GS, and DRIVE, respectively. Our OD segmentation result, in terms of mIoU, outperforms the state-of-the-art results for IDRiD and DRIVE datasets, whereas it outperforms state-of-the-art results concerning mean sensitivity for RIMONE and DRISHTI-GS datasets. The DRNet localizes the OD center 
with mean Euclidean Distance (mED) of 20.23 and 13.34 pixels, respectively, for IDRiD and HRF datasets; it outperforms the state-of-the-art by 4.62 pixels for IDRiD dataset. The DRNet also successfully localizes the Fovea center with mED of 41.87 pixels for the IDRiD dataset, 
outperforming the state-of-the-art by 1.59 pixels for the same dataset.
The proposed DRNet, for OD segmentation, achieves mean Intersection over Union (mIoU) of 0.845, 0.901, 0.933, and 0.920 for IDRiD, RIMONE,
DRISHTI-GS and DRIVE, respectively. Our OD segmentation result, in terms of mIoU, outperforms the state-of-the-art results for 
IDRiD and DRIVE datasets, whereas it outperforms state-of-the-art results concerning mean sensitivity for RIMONE and DRISHTI-GS datasets. The DRNet localizes the OD center with mean Euclidean Distance (mED) of 20.23 and 13.34 pixels, respectively, for IDRiD and HRF datasets; it outperforms the state-of-the-art by 4.62 pixels for IDRiD dataset. The DRNet also successfully localizes the Fovea center with mED of 41.87 pixels for the IDRiD dataset, outperforming the state-of-the-art by 1.59 pixels for the same dataset." 

# Summary. An optional shortened abstract.
summary: ''

tags:
- Diabetic retinopathy and glaucoma 
- Ophthalmology
- Skip connection 
- Residual skip connection
- Image segmentation
- Object localization 
- UNet
featured: true
url_code: https://github.com/kamruleee51/DRNet_Segmentation_Localization_OD_Fovea

  

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Workflow of the proposed DRNet'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []


---
