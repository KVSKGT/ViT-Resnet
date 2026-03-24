# Hybrid Vision Transformer + ResNet for Pneumonia Detection

## 📌 Project Overview
This project presents a Hybrid Deep Learning Model that combines the strengths of Convolutional Neural Networks (ResNet) and Vision Transformers (ViT) for Pneumonia Detection from Chest X-ray images.

ResNet is used for extracting strong local spatial features, while Vision Transformer captures global contextual relationships in the image. The hybrid architecture improves classification performance compared to using a single model.

---

## 📊 Dataset
The model is trained on a Chest X-ray dataset for Pneumonia detection.

Dataset contains:
- Normal cases
- Pneumonia infected cases

Dataset Source: *(Add dataset link here — Kaggle / NIH / etc.)*

---

## 🧠 Model Architecture
The proposed hybrid model consists of:

1. **ResNet Backbone**
   - Extracts deep spatial features from input images.

2. **Vision Transformer Encoder**
   - Processes extracted features to learn global attention relationships.

3. **Fully Connected Classification Head**
   - Outputs binary classification (Normal / Pneumonia).

---

## ⚙️ Training Details
- Framework: PyTorch  
- Loss Function: Cross Entropy Loss  
- Epochs: 10
- Image Size: 224*224
- Batch Size: 326

---

## 📈 Results
The hybrid model achieved:

- Training Accuracy: 0.8910
- F1 Score: 0.9183 
- ROC-AUC: 0.9655


## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/KVSKGT/ViT-Resnet.git
cd ViT-Resnet
