# Mammographic Anomaly Analysis

This repository contains the work carried out for the analysis of mammographic images, focusing on the detection and classification of anomalies. Our project utilized the **MIAS (Mammographic Image Analysis Society) dataset** to develop and evaluate several machine learning models.

## Project Overview

The primary goal of this project was to explore different approaches for assisting in the diagnosis of breast abnormalities from mammograms. We developed three distinct types of models to address various aspects of this challenge:

1.  **Benign/Malignant Tumor Classifier (Textual/Clinical Features)**:
    This model focuses on classifying tumors as benign or malignant based solely on textual or clinical features extracted from patient data. It leverages non-imaging information to provide a diagnostic prediction.

2.  **Benign/Malignant Tumor Classifier (Image-Based)**:
    This model performs classification of tumors (benign/malignant) directly from the mammographic images. It analyzes visual patterns and characteristics within the images to make its predictions.

3.  **Multimodal Classifier**:
    To enhance diagnostic accuracy, we developed a multimodal model that synergistically combines the strengths of the textual/clinical classifier and the image-based classifier. This model integrates information from both data types to provide a more comprehensive and robust prediction of tumor malignancy.

4.  **Object Detection Model for Anomaly Detection**:
    Beyond classification, we implemented an object detection model, specifically based on the **YOLOv8n-p2** architecture, to accurately pinpoint and localize anomalies (such as masses or microcalcifications) within the mammographic images. This model is crucial for identifying the precise location of potential pathologies.

Our comprehensive approach aims to contribute to more accurate and efficient mammographic analysis, ultimately aiding medical professionals in early diagnosis and patient care.
