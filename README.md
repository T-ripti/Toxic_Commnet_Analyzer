# Toxic Comment Classification
![Project Logo](![image](https://github.com/user-attachments/assets/47450d1a-d162-4fe7-8a09-087d189751b7))

This repository contains the implementation of a **Toxic Comment Classification** project, which utilizes machine learning to detect and categorize toxic online comments. The primary goal is to create a safer online environment by identifying harmful content efficiently.

---

## 📑 **Project Overview**

Toxic comments often disrupt online platforms, ranging from social media to forums. This project uses a neural network-based approach to classify comments into six categories:
- Toxic
- Severe Toxic
- Obscene
- Threat
- Insult
- Identity Hate

### **Objective**
- Develop a classifier to identify toxic comments and prevent the spread of hate speech and cyberbullying.
- Utilize a labeled dataset to train and evaluate multiple machine learning models.

---

## 🧩 **Dataset**

The dataset used is from [Kaggle's Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data). It includes over 150,000 Wikipedia comments, labeled into six toxicity categories. The data underwent cleaning and balancing to improve model accuracy.

---

## 🛠️ **Key Features**

1. **Data Preprocessing**:
   - Cleaned text using regular expressions.
   - Balanced the dataset to address class imbalances.

2. **Model Development**:
   - Evaluated various machine learning models, including logistic regression, LSTM, and CNNs.
   - Implemented a hybrid LSTM + CNN model for optimal performance.

3. **Web Interface**:
   - Built using **Gradio** for real-time toxic comment analysis.

4. **Evaluation Metrics**:
   - Achieved high accuracy and minimized false positives to encourage constructive dialogue.

---

## 📈 **Results**

- The hybrid LSTM-CNN model achieved the best performance.
- Successfully classified comments into the six categories with significant accuracy.
- Addressed class imbalance issues through custom preprocessing and data augmentation techniques.

---

## 📸 **Screenshots**

### 1. **Home Page of Gradio Interface**
![Home Page](./path-to-homepage-screenshot.png)

### 2. **Toxic Comment Analysis Results**
![Analysis Results](./path-to-analysis-results-screenshot.png)

### 3. **Model Training Accuracy Plot**
![Training Accuracy](./path-to-training-accuracy-plot.png)

---
## 🖥️ **How to Use**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/toxic-comment-classification.git

---

## 🔮 **Future Scope**

Explore advanced data augmentation techniques for better class distribution.
Combine bidirectional LSTM and GRUs for improved text classification.
Increase the model's robustness for longer and more complex comments.

---

## 📚 **References**
- Kaggle Toxic Comment Classification Dataset: Link
- Sahiladhav's Medium Article on Inappropriate Comment Scanner: Link

---

## 👩‍💻 **Contributors**
1. Tripti Patel
2. Hardik Dwivedi
3. Abhishek Chauhan
