# ✍️ Handwritten Digit Recognition
### A Custom Dataset, CNN Training & Deployment Project

**Qiyas AI and Data Science Program — Section 2**  
**Instructor:** Fantahun (PhD)

---

### 👥 Done by

| # | Name | Student ID |
|---|------|------------|
| 1 | Sofiya Yasin | qiyas-2026-002375 |

---

## 📋 Project Overview

This project implements a complete handwritten digit recognition pipeline using a custom dataset collected from different people.

The project follows the required pipeline:

```text
RAW PHOTOS
   ↓
Quality Control
   ↓
Crop Digit
   ↓
Grayscale
   ↓
Lighting / Background Normalization
   ↓
Center Digit
   ↓
Resize → 32×32
   ↓
Normalize → [0,1]
   ↓
Train / Validation / Test Split
   ↓
Augmentation ONLY on Training
   ↓
Small CNN Training
   ↓
Evaluation on Untouched Test Set
   ↓
Deployment

---

## 📊 Dataset

The model was trained on a custom handwritten digit dataset containing:

- 10 digit classes (`0` through `9`)
- 100 images for each digit
- 1,000 images in total

The images were collected from different people to improve variation in handwriting styles.

## 🧠 Model

The project uses a small Convolutional Neural Network (CNN). Before training, images are cropped, converted to grayscale, normalized, centered, resized to `32×32`, and split into training, validation, and test sets. Data augmentation is applied only to the training set.

## ✅ Result

The updated model achieved approximately **93% test accuracy** on the untouched test set.

## 🚀 Prediction Interface

The notebook also includes an upload interface that allows a user to provide a handwritten digit image and receive the model's predicted digit and confidence score.
