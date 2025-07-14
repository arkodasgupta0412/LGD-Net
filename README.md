# LGLD-Net

**LGLD-Net** is a lightweight Global and Local feature based Dual-stream neural network designed for efficient and accurate medical image classification. It combines a **Local Feature Aggregator (LFA)** for fine-grained textures, a **Global Context Encoder (GCE)** for long-range dependencies, and an **Adaptive Fusion Module**, all in just **161K parameters**, achieving state-of-the-art performance across multiple benchmark datasets.

---

## Abstract

Microscopic image analysis provides vital information at the cellular level. However, most deep learning models struggle to jointly capture fine-grained and global features and often remain computationally expensive.  
To this end, we propose a compactly designed lightweight model (**161K parameters**), called **A lightweight Global and Local feature based Dual-stream Neural Network (LGLD-Net)**.  

LGLD-Net uses:
- **Involution-based patch stem** to capture fine-grained local textures, and  
- **Fourier-based global stream** to model long-range dependencies and contextual features.
- An **adaptive fusion module** dynamically balances local and global features for optimal representation.
- The proposed LGLD-Net achieves **state-of-the-art performance** on two microscopic image datasets:
    - **ALL**
    - **Raabin-WBC**

---

## Keywords

**Microscopic Image Classification** · **Lightweight CNN** · **Local and Global Features** · **Dual-branch Neural Network**
