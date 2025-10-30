# Smart-Waste-Classification-using-CNN
A Deep Learning Approach for Sustainable Waste Management .This project uses  Convolutional Neural Networks (CNN) with  Transfer Learning (MobileNetV2) to classify waste images as  Organic  or Recyclable, promoting sustainability and supporting UN SDG 12 – Responsible Consumption and Production
Project Overview

With the surge of urban waste, manual segregation is inefficient and hazardous.  
This AI-based system automates waste identification from images, helping streamline recycling and reduce landfill load.

---

🧩 Problem Statement

Improper segregation of waste is a growing global challenge. Manual sorting is time-consuming, error-prone, and unsustainable.  
This project leverages CNN-based deep learning to classify waste images accurately, enhancing recycling efficiency and supporting green technology initiatives.

---

 ⚙️ Model Summary (Week 1)
- Base CNN with 2 convolutional layers
- Trained for 5 epochs
- Accuracy (Week 1 baseline): ~85%

---


⚙️ Tools & Technologies

- **Python**, **TensorFlow/Keras**, **Matplotlib**, **Pillow**
- **Google Colab** for training
- **Kaggle Dataset:** [Waste Classification Data](https://www.kaggle.com/datasets/techsash/waste-classification-data)

---
 📊 Model Architecture

MobileNetV2 → GlobalAveragePooling → Dense (Softmax) → Output  
> Transfer learning approach fine-tuned for binary waste classification.

---

