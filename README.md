# TeaLeaftNet: Tea Leaf Disease Detection System 🍃

**Course:** ICT 3212 - Introduction to Intelligent Systems  
**Phase:** 03 - Image Classification Model Implementation (Implementation 1) 
**University:** Rajarata University of Sri Lanka 

## 👥 Team: Quantum Coders
* **M.J.H.A.P. Madushani** (Leader) - ICT/2022/142
* **M.K.H.K. Madushani** - ICT/2022/107
* **W.K.D. Bhagya** - ICT/2022/110
* **M.T. Rathnayake** - ICT/2022/114
* **M.G.J. Sinty** - ICT/2022/043

## 📌 Project Overview
TeaLeaftNet is an intelligent image classification system designed to automatically identify common diseases in tea leaves. 
This repository contains the code and models for **Implementation 1**, which focuses on designing a baseline Image Classification System using a Convolutional Neural Network (CNN). 

At this stage, the focus is on building a correct, functional pipeline from data loading to evaluation, rather than hyper-optimized performance.

## 🗄️ Dataset
* **Source:** "Tea Sickness Dataset" (Kaggle) 
* **Classes (4):** `Healthy`, `Anthracnose`, `Algal_Leaf`, `Bird_Eye_Spot`
* **Preprocessing applied:** Resized to 224x224, Normalized (0-1), converted to TensorFlow tensors.
* **Split:** 80% Training / 20% Validation.

## 🧠 Baseline Model (Implementation 1)
* **Architecture:** Custom Convolutional Neural Network (CNN) 
* **Layers:** 3x (Conv2D + MaxPooling2D) -> Flatten -> Dense (128) -> Output Dense (4 classes with Softmax).
* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy

## 📂 Repository Contents
* `TeaLeaftNet_Implementation1.ipynb`: The Google Colab source code containing dataset preparation, model building, training, and evaluation.
* `tealeaftnet_baseline.h5`: The saved baseline model file.
* *(Optional: Add your PDF report here if you uploaded it to GitHub).*

## 🚀 How to Run
1. Download the "Tea Sickness Dataset" from Kaggle and upload the 4 specific class folders to your Google Drive.
2. Open the `.ipynb` notebook in Google Colab.
3. Update the dataset path to match your Google Drive directory.
4. Run all cells sequentially to train the model and output the evaluation metrics and confusion matrix.

---
*Note: This model will be further optimized using data augmentation, regularization, and hyperparameter tuning in Implementation 2.*
