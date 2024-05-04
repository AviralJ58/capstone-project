#   Unleashing the Power of Cognitive Learning for Brain Tumour Diagnosis

This project aims to leverage cognitive learning techniques to enhance the accuracy and efficiency of brain tumour diagnosis. By integrating deep learning models for image analysis and natural language processing (NLP) algorithms for information retrieval, the system provides a comprehensive platform for medical professionals and patients to better understand and manage brain tumours.

## Overview

The system consists of two main components: a deep learning model for brain tumour detection and classification, and an NLP module for answering user queries and providing relevant information about brain tumours. The deep learning model analyzes MRI scans to identify the presence and type of brain tumour, while the NLP module interacts with users to address their inquiries regarding diagnosis, treatment options, and other related topics.

## How it Works

1.  **Deep Learning Model**:
    
    -   The system starts by preprocessing MRI scans, including normalization and resizing.
    -   A deep learning model, trained on a dataset of labelled MRI scans, is used to detect and classify brain tumours into different types (e.g., glioma, meningioma, pituitary).
    -   The best-performing model is selected based on training and validation accuracy metrics.
    -   Upon receiving a new MRI scan, the model predicts the presence and type of brain tumour with high accuracy.
2.  **NLP Module**:
    
    -   If the user has queries or requires additional information about brain tumours, they can interact with the NLP module.
    -   The NLP module accesses a knowledge base to provide accurate and verified information in response to user queries.
    -   By employing cognitive learning techniques, the NLP module can understand and interpret user inquiries, providing tailored explanations and recommendations.
    -   The module also supports follow-up questions and maintains a context.

## Architecture Diagram

Please find the architecture diagram illustrating the components and workflow of the system in the 'architecture_drawio.png' file located in the repository.

![Architecture Diagram](https://github.com/AviralJ58/capstone-project/blob/main/architecture.drawio.png?raw=true)
