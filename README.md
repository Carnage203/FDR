# FDR
Face Detection and Recognition using Yolov5 and SSD Mobilenet trained on **custom dataset**.
## Overview

**FDR** (Face Detection and Recognition) is an open-source project dedicated to developing robust, accurate, and extensible solutions for detecting and recognizing faces in images and videos. Leveraging Python and Jupyter Notebooks, FDR is structured for both educational and practical use cases—making it suitable for researchers, students, and engineers interested in computer vision and facial analysis.

---

## Project Objectives

- **Demonstrate modern face detection and recognition techniques** using real-world datasets and scenarios.
- **Provide a modular, extensible codebase** that allows users to easily experiment with and extend various face analysis approaches.
- **Enable reproducible research and rapid prototyping** through interactive Jupyter Notebooks.
- **Facilitate understanding and visualization** of the complete face recognition pipeline, from data preprocessing to evaluation.

---

## Project Structure

The repository is organized as follows:

```
FDR/
│
├── notebooks/          # Main Jupyter Notebooks for detection, recognition, and experiments
├── data/               # Sample datasets and data loading scripts
├── models/             # Pretrained models or model definition scripts
├── utils/              # Utility functions for preprocessing, visualization, etc.
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```

---

## Features

- **Face Detection**:  
  Uses state-of-the-art algorithms (such as Haar Cascades, HOG + SVM, or deep learning models like MTCNN or RetinaFace) to accurately detect faces in static images or video streams.

- **Face Recognition**:  
  Extracts features from detected faces and compares them using embeddings (e.g., FaceNet, VGGFace, ArcFace) for identification or verification tasks.

- **Preprocessing & Augmentation**:  
  Includes tools for image normalization, face alignment, and data augmentation to improve model robustness.

- **Visualization Tools**:  
  Provides code for displaying detection and recognition results, confusion matrices, ROC curves, and more, directly within Jupyter Notebooks.

- **Evaluation Metrics**:  
  Implements accuracy, precision, recall, F1-score, and other relevant metrics for quantitative assessment of models.

- **Extensibility**:  
  Easily plug in your own datasets, models, or preprocessing modules by following the provided interface and notebook structure.

---
![Face Detection 1](https://github.com/user-attachments/assets/2fac339c-3c72-4a28-89a8-5c4c325dc4de)
![Face Detection 2](https://github.com/user-attachments/assets/6a6281c7-f848-41a2-9395-15192d061c9b)
![Face Detection 3](https://github.com/user-attachments/assets/c54fdb7e-6ebe-4fa0-b605-7094d9334c12)
![Face Detection 4](https://github.com/user-attachments/assets/39ed0817-8a47-462b-859d-78e48146d125)
