# Plant Disease Detection with Deep Learning 

This project uses Convolutional Neural Networks (CNNs) to classify plant leaf diseases based on the PlantVillage dataset. The primary goal is to develop a high-accuracy, scalable, and interpretable deep learning model that assists in early disease diagnosis in agriculture—supporting food security and modern farming.

---

# Project Overview

- Topic: Image Classification for Plant Leaf Diseases
- Frameworks: TensorFlow, Keras, OpenCV, Matplotlib
- Dataset: [PlantVillage](https://www.kaggle.com/datasets/mohitsingh1804/plantvillage)
- Accuracy Achieved: 89.35% validation accuracy**
- F1 Score: 0.8913
- Use Case: Agriculture diagnostics (with parallels drawn to medical imaging)

---

# Objectives

- Develop a CNN model for multiclass image classification.
- Analyze and compare the performance of the model using key metrics.
- Investigate the effect of data augmentation and regularization.
- Demonstrate real-world applicability in agriculture and healthcare.
- Reflect on limitations and suggest improvements or extensions.

---

# Model Architecture

- CNN Layers: 3 Conv-Pool blocks, Dense layers, Dropout regularization.
- Optimizer: RMSprop
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Augmentation: Rotation, Flip, Shift, Zoom
- Epochs: 10
- Classes: 38 plant disease and healthy categories

---

## 📊 Key Results

| Metric         | Score     |
|----------------|-----------|
| Validation Accuracy | 89.35%   |
| F1 Score       | 0.8913    |
| ROC-AUC        | 0.9965    |

- Confusion Matrix: Provided to analyze class-level performance
- ROC Curves: Evaluated for 10 class subsets
