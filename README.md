# Skin-Cancer-Classification-Using-ViT16-Base

This repository presents a deep learning project focused on **skin cancer classification** using the **Vision Transformer (ViT-16 Base)** architecture. The model was trained on the **HAM10000 dataset** sourced from Kaggle, achieving solid classification performance across seven skin lesion categories.

---

## 📌 Project Highlights

- ✅ Implemented **ViT-16 Base** for image classification.
- ✅ Used **HAM10000** dataset with 7 classes of skin lesions.
- ✅ Achieved **80.04% test accuracy** after 30 epochs.
- ✅ Built in **PyTorch** and trained using stratified and augmented data.
- ✅ Efficient training with monitoring of `loss` and `accuracy` trends.

---

## 📊 Final Model Performance

| Epoch | Train Accuracy | Test Accuracy | Train Loss | Test Loss |
|-------|----------------|---------------|------------|-----------|
| 1     | 63.60%         | 75.27%        | 1.0096     | 0.6706    |
| 10    | 76.51%         | 78.55%        | 0.6527     | 0.6120    |
| 20    | 77.56%         | 79.97%        | 0.6196     | 0.6150    |
| **30**| **78.09%**     | **80.04%**    | **0.6067** | **0.6212**|

🔁 *Training continued for 30 epochs with consistent improvements in both loss and accuracy.*

---

## 📂 Dataset: [HAM10000 (Kaggle)](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

- HAM10000: Human Against Machine with 10000 training images.
- 7 skin lesion categories:
  - **akiec**: Actinic keratoses
  - **bcc**: Basal cell carcinoma
  - **bkl**: Benign keratosis-like lesions
  - **df**: Dermatofibroma
  - **nv**: Melanocytic nevi
  - **vasc**: Vascular lesions
  - **mel**: Melanoma

---

## 🧠 Model: Vision Transformer (ViT-16 Base)

- Pretrained on ImageNet
- Patch-based tokenization
- Positional encodings and transformer layers
- CLS token used for classification
- Final linear layer with 7 output nodes (softmax)

---
