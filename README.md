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
Week 2 – Smart Waste Classification using CNN
🌱 AI for Sustainability Project | Theme: Sustainable Waste Management using Deep Learning
🎯 Objectives for Week 2

Understand and implement Convolutional Neural Networks (CNNs) for image classification.

Learn about Transfer Learning and how to apply pretrained models like MobileNetV2.

Prepare dataset (waste images) for training and testing.

Train, evaluate, and visualize CNN model performance using Google Colab.

Achieve high accuracy in classifying images as Organic or Recyclable.

🧩 Tasks Completed
Task	Description	Tools Used
✅ Dataset Preparation	Organized Kaggle Waste Classification dataset into TRAIN and TEST folders	Google Drive, Colab
✅ Model Selection	Used MobileNetV2, a CNN architecture for transfer learning	TensorFlow / Keras
✅ Model Training	Trained model for 10 epochs on the dataset with 90%+ accuracy	Google Colab (GPU)
✅ Visualization	Plotted training and validation accuracy/loss graphs	Matplotlib
✅ Model Saving	Exported trained model as waste_classifier.h5 and stored in Drive	Keras, Google Drive
🧠 Concepts Learned

Convolutional Neural Networks (CNNs):
Learned how CNN layers automatically extract spatial features like edges, textures, and patterns from images.

Transfer Learning:
Understood how to reuse pretrained models (MobileNetV2) to improve performance and reduce training time.

Data Augmentation & Preprocessing:
Applied normalization and image resizing using ImageDataGenerator.

Model Evaluation:
Learned how to interpret accuracy, loss, and confusion matrices for assessing performance.

⚙️ Tools & Technologies

- **Python**, **TensorFlow/Keras**, **Matplotlib**, **Pillow**
- **Google Colab** for training
- **Kaggle Dataset:** [Waste Classification Data](https://www.kaggle.com/datasets/techsash/waste-classification-data)

---
 📊 Model Architecture

MobileNetV2 → GlobalAveragePooling → Dense (Softmax) → Output  
> Transfer learning approach fine-tuned for binary waste classification.

---

