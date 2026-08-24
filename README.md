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