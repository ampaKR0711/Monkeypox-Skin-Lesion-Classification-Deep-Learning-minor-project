<div align="center">

# 🧬 Monkeypox Skin Lesion Classification using Deep Learning

### 🚀 Minor Project • KIIT University  
### 🧠 Deep Learning • Healthcare AI • Medical Image Analysis

<img src="https://img.shields.io/badge/Domain-Healthcare%20AI-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/Framework-TensorFlow-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge" />
<img src="https://img.shields.io/badge/Model-CNN%20%7C%20VGG16%20%7C%20EfficientNet-success?style=for-the-badge" />
<img src="https://img.shields.io/badge/Accuracy-99.55%25-brightgreen?style=for-the-badge" />

---

### 🔬 AI-Powered Monkeypox Detection using Hybrid Deep Learning Architecture

</div>

---

# 📌 Overview

This project presents an advanced **Deep Learning-based healthcare diagnostic system** for the automated classification of **Monkeypox skin lesions** using medical image analysis and Artificial Intelligence.

The system combines:

- 🧠 Convolutional Neural Networks (CNNs)
- 🔥 Transfer Learning
- 🎯 Attention Mechanisms
- 📊 Explainable AI (Grad-CAM)

to achieve highly accurate Monkeypox classification.

The proposed model assists healthcare systems by enabling intelligent and automated disease screening through AI-assisted image diagnosis.

---

# ❗ Problem Statement

Monkeypox (Mpox) shares visual similarities with diseases such as:

- Chickenpox
- Measles
- Other dermatological infections

Manual diagnosis is often:
- time-consuming
- dependent on specialists
- difficult in low-resource regions

This project aims to build an intelligent AI system capable of:

✅ Detecting Monkeypox skin lesions  
✅ Distinguishing Mpox from other skin diseases  
✅ Improving diagnostic accuracy  
✅ Supporting healthcare professionals using AI  

---

# 🎯 Project Objectives

- Develop a highly accurate Monkeypox classification system
- Apply transfer learning for medical image diagnosis
- Improve healthcare diagnostic reliability
- Compare performance against existing research models
- Integrate explainable AI techniques

---

# 🏗️ Proposed Architecture

```text
Input Skin Lesion Image
            │
            ▼
Image Preprocessing
            │
            ▼
 ┌──────────────────────┐
 │      VGG16 Branch    │
 └──────────────────────┘
            │
            ▼
 ┌──────────────────────┐
 │ EfficientNetB4 Branch│
 └──────────────────────┘
            │
            ▼
 Attention-Based Fusion
            │
            ▼
 Dense Classification Layers
            │
            ▼
 Monkeypox / Other Prediction
```

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| TensorFlow | Deep Learning Framework |
| Keras | Model Development |
| CNN | Image Classification |
| VGG16 | Transfer Learning |
| EfficientNetB4 | Advanced Feature Extraction |
| Grad-CAM | Explainable AI |
| Jupyter Notebook | Development Environment |

---

# 🧠 Deep Learning Features

## 🔥 Transfer Learning

Pretrained ImageNet models were used to improve learning efficiency and classification performance.

---

## 🎯 Attention Mechanism

Attention layers help the model focus on critical lesion regions.

---

## 📊 Grad-CAM Visualization

Grad-CAM heatmaps visually explain the AI prediction process.

---

## 🧬 Hybrid CNN Architecture

Combines strengths of:
- VGG16
- EfficientNetB4

for improved classification reliability.

---

# 📈 Experimental Results

<div align="center">

| Metric | Performance |
|---|---|
| ✅ Accuracy | **99.55%** |
| ✅ Precision | **99.24%** |
| ✅ Recall | **99.56%** |
| ✅ F1-Score | **99.55%** |
| ✅ AUC Score | **0.9999** |

</div>

---

# 🏆 Performance Comparison

The proposed model outperformed several existing approaches including:

- MonkeyNet
- InceptionV3
- VGG19
- MobileNetV2
- SwinTransformer

The hybrid architecture demonstrated:
- higher reliability
- stronger generalization
- better classification consistency

---

# 🔬 Explainable AI Support

The system integrates **Grad-CAM visualizations** to improve transparency in medical predictions.

This helps:
- healthcare professionals
- medical researchers
- diagnostic systems

understand why the model classified a lesion as Monkeypox.

---

# 🚨 Challenges Faced

## 📉 Limited Dataset Availability

Medical datasets for Monkeypox were limited.

### ✅ Solution
Used:
- transfer learning
- augmentation
- pretrained architectures

---

## 🔍 Disease Similarity

Monkeypox visually resembles other skin diseases.

### ✅ Solution
Implemented:
- attention mechanisms
- hybrid feature extraction

---

## ⚠️ Overfitting Risk

Deep learning models may overfit on small medical datasets.

### ✅ Solution
Used:
- dropout
- regularization
- EarlyStopping
- cross-validation

---

# 🌍 Real-World Importance

This project demonstrates how AI can assist healthcare systems by enabling:

✅ Faster disease diagnosis  
✅ Intelligent healthcare screening  
✅ Medical image automation  
✅ AI-assisted healthcare analytics  

especially in regions with limited medical resources.

---

# 🚀 Future Improvements

- 📱 Mobile healthcare integration
- ☁️ Cloud deployment
- 🏥 Clinical deployment systems
- 🧠 Multi-disease classification
- ⚡ Lightweight edge AI models
- 🔬 Advanced explainable healthcare AI

---

# 📚 Academic Information

| Field | Details |
|---|---|
| 🎓 Project Type | Minor Project |
| 🧬 Domain | Deep Learning & Healthcare AI |
| 🏫 Institution | KIIT University |
| 🔬 Research Area | Medical Image Classification |

---

# 👨‍💻 Contributors & Individual Contributions

---

## 🔹 Ampa Ranjan  
### 📌 Research, Experimental Evaluation, Explainable AI & Documentation

### 🔬 Technical Contributions
- Worked on the complete data preprocessing pipeline for the Monkeypox skin lesion dataset containing 5,799 medical images.
- Implemented image normalization and augmentation techniques to improve model generalization and reduce overfitting.
- Contributed to the experimental evaluation and performance analysis of the hybrid deep learning architecture.
- Worked on Explainable AI (XAI) implementation using Grad-CAM heatmaps to visualize model decision-making and lesion attention regions.
- Assisted in validating the effectiveness of the dual-branch architecture in identifying subtle lesion patterns and improving sensitivity.

### 📊 Research Findings
- Observed that the hybrid architecture achieved high sensitivity and reliable classification performance for Monkeypox detection.
- Contributed to the interpretation of Grad-CAM visualizations which demonstrated meaningful lesion-focused attention by the model.

### 📝 Documentation Contributions
- Prepared the Result Analysis and References sections of the project report.
- Designed high-resolution architectural diagrams, Precision-Recall plots, Correlation graphs, and result visualization figures used in the final documentation.

### 🎤 Presentation & Demonstration Contributions
- Designed and structured the project presentation slides.
- Prepared visual explanation materials for experimental results and model evaluation.
- Organized the Results and Discussion section during the project presentation and demonstration.

---

## 🔹 Milan Mipsita Jena  
### 📌 Research Design, Dataset Management & Evaluation Framework

### 🔬 Technical Contributions
- Conducted a systematic literature review to analyze existing Monkeypox detection approaches and identify research gaps.
- Managed dataset curation and preprocessing workflows for 5,799 medical images.
- Ensured class balancing and dataset suitability for 5-fold stratified cross-validation.
- Assisted in defining the training and evaluation strategy to improve model consistency and reduce false negatives.
- Contributed to the overall experimental methodology and evaluation framework.

### 📊 Research Findings
- Helped establish the need for a hybrid architecture combining VGG16 and EfficientNetB4 for improved feature extraction and classification reliability.
- Contributed to improving model stability through structured validation methodology.

### 📝 Documentation Contributions
- Drafted:
  - Chapter 1 – Introduction
  - Chapter 2 – Literature Review
  - Chapter 4 – Materials and Methods
  - Chapter 5 – Research Gap
  - Chapter 8 – Result Analysis
  - Chapter 9 – Conclusion
- Managed overall report integration, formatting, consistency, and plagiarism compliance.

### 🎤 Presentation & Demonstration Contributions
- Prepared presentation slides covering:
  - research background
  - problem statement
  - methodology overview
  - future scope
- Assisted in organizing the project demonstration workflow.

### 🌐 GitHub
GitHub:  
https://github.com/Milan-corespace

---

## 🔹 Mayank Gupta  
### 📌 Hybrid Architecture Development, Feature Fusion & Model Optimization

### 🔬 Technical Contributions
- Contributed to the development of the hybrid deep learning architectural framework.
- Worked on integrating VGG16 and EfficientNetB4 dual-stream feature extraction branches.
- Configured Squeeze-and-Excitation (SE) channel attention modules for improved feature refinement.
- Assisted in implementing the attention-based feature fusion layer for combining multi-branch outputs.
- Contributed to the multi-stage training pipeline and 5-fold stratified cross-validation framework to ensure robust model performance.
- Participated in optimizing training stability and minimizing false negatives.

### 📊 Research Findings
- Observed that the fusion-level attention mechanism effectively reconciled feature representations from both architectures.
- Contributed to achieving high model accuracy and strong classification consistency.

### 📝 Documentation Contributions
- Assisted in documenting:
  - Chapter 6 – Implementation
  - Chapter 7 – Standards Adopted
- Prepared algorithmic flowcharts and technical descriptions related to model optimization and backend architecture.

### 🎤 Presentation & Demonstration Contributions
- Prepared presentation slides explaining:
  - hybrid model architecture
  - backend processing
  - logical data flow
- Assisted in organizing software demonstrations and technical workflow presentations.

---

# 🤝 Research Collaboration & Open Innovation

This project reflects collaborative research efforts in the intersection of:

- 🧠 Artificial Intelligence
- 🧬 Healthcare Analytics
- 🔬 Medical Image Classification
- 📊 Explainable AI (XAI)
- 🚀 Deep Learning Research

The development process involved continuous experimentation, architecture refinement, evaluation analysis, documentation structuring, and collaborative academic discussion among contributors.

We strongly believe in:
- collaborative problem solving
- interdisciplinary AI research
- responsible healthcare AI systems
- transparent and explainable machine learning

This repository represents both a technical implementation and a research-oriented learning initiative focused on real-world healthcare impact.

---

# 🔒 License & Copyright

## ⚠️ All Rights Reserved

Copyright © 2026  
Ampa Ranjan, Milan Mipsita Jena, and Mayank Gupta

This repository and all associated files including:

- source code
- documentation
- workflows
- architectures
- figures
- research content
- implementation details

are protected under copyright law.

❌ Unauthorized copying, reproduction, redistribution, modification, publication, or academic submission is strictly prohibited.

Any unauthorized usage may result in:
- copyright claims
- repository takedown requests
- academic integrity violations

This repository is intended strictly for:
✅ academic  
✅ research  
✅ portfolio purposes  

---
# 📬 Contact Information

## 🔹 Ampa Ranjan
KIIT University

## 🔹 Milan Mipsita Jena
GitHub:  
https://github.com/Milan-corespace

## 🔹 Mayank Gupta

---

<div align="center">

# ⭐ AI for Healthcare • Deep Learning Research • KIIT University ⭐

</div>
