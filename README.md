# Clinical-Report-Guided-Thyroid-Nodule-Segmentation
The dataset and code of the paper 'Adversarial Keyword Extraction and Semantic-Spatial Feature Aggregation for Clinical Report Guided Thyroid Nodule Segmentation', PRCV 2023.

# Introduction
Existing thyroid nodule segmentation methods are primarily developed based on ultrasound images, which generally neglects the clinical reports that include rich semantic information for nodules. However, current text guided segmentation methods for natural images are not applicable to the image-report thyroid nodule dataset, due to the many-to-one correspondence between images and reports in current data.
To this end, we propose a clinical report guided thyroid nodule segmentation framework with Adversarial Keyword Extraction (AKE) module to extract keywords from reports and Semantic-Spatial Feature Aggregation (SSFA) module to integrate reports into the segmentation model. To alleviate the many-to-one correspondence issue, we devise the AKE module to highlight the keywords about current ultrasound images from clinical reports with a keywords mask, which adopts adversarial learning to encourage the mask generator to mask out the useful descriptions to boost segmentation performance. We further propose the SSFA module to effectively and efficiently map semantic information from reports to each pixel of spatial features, so as to emphasize the target regions. Moreover, we manually collect a clinical Reports Assisted Thyroid Nodule segmentation dataset (RATN), which includes the ultrasound images, the pixel-wise nodule segmentation annotation, and the clinical reports. Extensive experiments have been conducted on the RATN dataset, and the results prove the effectiveness and computational efficiency of the proposed method over the existing methods. The source code and RATN dataset are to be released for public access.

# Architecture
Overview of the proposed frameworks.


# Instructions for Code:

1. Requirements:

python3.7-3.9 pytorch >= 1.5 torchvision >= 0.6.1 cuda >= 10.1 transformers = 4.21.3

2. Code and Dataset:

The code of this project is being standardized and reconstructed. After refactoring and review by all authors of the paper (we are working hard on this process, it will not take too long), the complete code and RATN dataset will be released.
