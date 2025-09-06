# Machine_Learning_in_Robotics_course2025

This repository contains solutions for a machine learning coursework involving supervised and unsupervised techniques applied to computer vision tasks. All implementations are in Python using Jupyter Notebooks.

## **Tasks**

- [ ] Image Classification – Custom CNN and pre-trained models (transfer learning).

- [ ] Image Segmentation – Mask prediction using IoU as a performance metric.

- [ ] Image Clustering – Unsupervised grouping of images.

- [ ] Autoencoders – Image reconstruction, fusion, and denoising.

## **Dataset**
[link](url)
•	Road scene images (colored) with corresponding binary masks.
•	Images may contain road signs or crosswalks.
•	Applied data normalization and data augmentation to improve training.
## **Key Results**

**Classification**

•	Custom CNN: 91.5% validation accuracy.
•	With data augmentation: 96.28% validation accuracy.
•	Pre-trained model (transfer learning): 95.03% validation accuracy.

**Segmentation**
•	IoU score: 0.679 average.

**Autoencoders**
•	Model with 64 channels: Loss < 0.01; better detail preservation after denoising.
•	Model with 32 channels: Loss; faster but lower reconstruction quality.

Full implementation and results are available in the notebooks.

