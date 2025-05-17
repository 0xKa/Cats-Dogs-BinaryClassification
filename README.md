# 🐶🐱 Cats vs Dogs Binary Classification

This is a deep learning project that classifies images of cats and dogs using Convolutional Neural Networks (CNNs) and Transfer Learning with MobileNetV2. The goal is to distinguish between cat and dog images with high accuracy.

---

## 🧠 Models Used

- ✅ **Custom CNN** with 3 convolutional layers (basic model)
- ✅ **MobileNetV2** pretrained on ImageNet (transfer learning)

---

## 🗂️ Dataset

- Source: [Kaggle - Cats and Dogs Image Classification](https://www.kaggle.com/datasets/samuelcortinhas/cats-and-dogs-image-classification)
- Structure:
  dataset/
  ├── train/
  │ ├── cats/
  │ └── dogs/
  └── test/
  ├── cats/
  └── dogs/

## 📦 Output

Trained model is saved as:

cat_dog_classifier.keras (basic CNN)

cat_dog_transfer_model.keras (MobileNetV2)

Includes plots for training accuracy and loss

## 📊 Results

| Model       | Final Val Accuracy |
| ----------- | ------------------ |
| Custom CNN  | \~53%              |
| MobileNetV2 | \~93%              |
