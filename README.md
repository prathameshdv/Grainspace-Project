# 🌾 Grainspace-Project

**Leveraging Pretrained Ensemble Models for Fine-grained Cereal Quality Inspection**

---

## 📄 Paper Link

[📘 Read the Paper (PDF)](https://github.com/prathameshdv/Adapted-Cat-and-Mouse-Based-Optimizer/blob/main/Documents/ICOA2025_ID214%20(1).pdf)

---

## 🧠 Overview

This repository contains the implementation for our research paper  
**“Leveraging Pretrained Ensemble Models for Fine-grained Cereal Quality Inspection”**,  
which explores the use of **deep learning ensemble architectures** for automated cereal grain classification using the **GrainSpace** dataset.

We utilize pretrained **ConvNeXt-Tiny** and **ResNet50** architectures on the *Wheat_R19-22_G600* subset and combine them via **logit-level ensembling** to achieve improved macro-F1 performance under class imbalance.

---

## 🧩 Key Highlights

- Fine-tuning **ConvNeXt-Tiny** and **ResNet50** models pretrained on ImageNet.  
- **Logit-level ensemble** fusion for robust feature aggregation.  
- Focus on **macro-F1** to handle imbalanced multi-class distribution.  
- Achieved **76.42% macro-F1**, outperforming individual models.  
- Designed for scalable agricultural visual inspection tasks.

---

## 📊 Results

| Model                             | Macro-F1 (%) |
|----------------------------------:|-------------:|
| ConvNeXt-Tiny (Pretrained)        | 73.32        |
| ResNet50 (Pretrained)             | 74.67        |
| Ensemble (ConvNeXt + ResNet)      | **76.42**    |

---

### 📈 Example Output

![Model Output Example](https://github.com/prathameshdv/Adapted-Cat-and-Mouse-Based-Optimizer/blob/main/Results/1500.png)

---

## 🧰 Repository Structure

