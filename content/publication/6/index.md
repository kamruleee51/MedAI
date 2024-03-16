---
title: "Detection, segmentation, and 3D pose estimation of surgical tools using convolutional neural networks and algebraic geometry"
authors:
- "Md Kamrul Hasan, Lilian Calvet, Navid Rabbani, Adrien Bartoli"
#date: "2020-04-2"
doi: "https://doi.org/10.1016/j.media.2021.101994"

url_video: https://youtu.be/Knp4JIhH3Yo
 

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Medical Image Analysis, Volume 70, 2021, 101994"
publication_short: "Medical Image Analysis, Volume 70, 2021, 101994"

abstract: "Surgical tool detection, segmentation, and 3D pose estimation are crucial components in Computer-Assisted Laparoscopy (CAL). The existing frameworks have two main limitations. First, they do not integrate all three components. Integration is critical; for instance, one should not attempt computing pose if detection is negative. Second, they have particular requirements, such as the availability of a CAD model. We propose an integrated and generic framework whose sole requirement for the 3D pose is that the tool shaft is cylindrical. Our framework makes the most of deep learning and geometric 3D vision by combining a proposed Convolutional Neural Network (CNN) with algebraic geometry. 
We show two applications of our framework in CAL: tool-aware rendering in Augmented Reality (AR) and tool-based 3D measurement. We name our CNN as ART-Net (Augmented Reality Tool Network). It has a Single Input Multiple Output (SIMO) architecture with one encoder and multiple decoders to achieve detection, segmentation, and geometric primitive extraction. These primitives are the tool edge-lines, mid-line, and tip. 
They allow the tool's 3D pose to be estimated by a fast algebraic procedure. The framework only proceeds if a tool is detected. 
The accuracy of segmentation and geometric primitive extraction is boosted by a new Full-resolution feature map Generator (FrG). 
We extensively evaluate the proposed framework with the EndoVis and new proposed datasets. We compare the segmentation results against several Fully Convolutional Networks (FCN) and U-Net variants. 
Several ablation studies are provided for detection, segmentation, and geometric primitive extraction. The proposed datasets are surgery videos of different patients. In detection, ART-Net achieves 100.0% in both average precision and accuracy. In segmentation it achieves 
81.0%  in mean Intersection over Union (mIoU) on the robotic EndoVis dataset (articulated tool), where it outperforms both FCN and UNet by 
4.5pp and 2.9pp, respectively. It achieves 88.2% mIoU on the remaining datasets (non-articulated tool). In geometric primitive extraction, ART-Net achieves 2.45 degrees and 2.23 degrees in mean Arc Length (mAL) error for the edge lines and mid-line, respectively, and 9.3 pixels in mean Euclidean distance error for the tooltip. Finally, regarding the 3D pose evaluated on animal data, our framework achieves 1.87 mm, 0.70 mm, and 4.80 mm mean absolute errors on the X, Y, and Z coordinates, respectively, and 5.94∘ angular errors on the shaft orientation. It achieves 2.59 mm and 1.99 mm in the tool head's mean and median location error evaluated on patient data. The proposed framework outperforms existing ones in detection and segmentation. Compared to separate networks, integrating the tasks in a single network preserves accuracy in detection and segmentation but substantially improves accuracy in geometric primitive extraction. Our framework has similar or better accuracy in 3D pose estimation while improving robustness against laparoscopy's very challenging imaging conditions. "

# Summary. An optional shortened abstract.
summary: ''

tags:
- Computer-assisted intervention
- CNNs
- Deep learning
- Image segmentation
- 3D pose estimation
- Augmented reality
- AI in medical imaging
- Medical image analysis
featured: true
url_code: "https://github.com/kamruleee51/ART-Net"


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ' Proposed framework for concurrent tool detection, segmentation, and geometric primitive extraction'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []


---
