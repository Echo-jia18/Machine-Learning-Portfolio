# Machine-Learning-Portfolio

## Undergraduate Projects

### 1. Vision Transformer-Based Vehicle Damage Analysis for Insurance Fraud Detection
   
Project introduction：

·Data Processing: Engineered an image classification pipeline using PyTorch to automatically detect fraudulent vehicle insurance claims. Mitigated class imbalance by integrating a WeightedRandomSampler into the DataLoader.

·Transfer Learning: Implemented a ViT model, leveraging pre-trained ImageNet weights. Froze the convolutional base and built a new classification head with Linear layers, ReLu activation, and optimized Dropout to adapt to the specific task.

·Model Optimization: Enhanced model performance by executing data preprocessing, hyper-parameter tuning, and dynamic threshold adjustments, increasing the macro F1 score to 0.94 on the test set.

file name: fraud_detection_project.py
