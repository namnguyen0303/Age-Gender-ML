# Age and Gender Prediction Using CNN and MLP

This project explores predicting age (regression) and gender (classification) from image data using two deep learning models: a **Convolutional Neural Network (CNN)** and a **Multilayer Perceptron (MLP)**. It compares performance, training time, and overfitting tendencies across tasks.

Link to download the dataset: https://susanqq.github.io/UTKFace/
---

## 🚀 Models Used

### 🧠 CNN (Convolutional Neural Network)
- **Used for**: Age (regression) & Gender (classification)
- **Strengths**: High accuracy, captures image features well
- **Weaknesses**: Slower training, more prone to overfitting

### 🔢 MLP (Multilayer Perceptron)
- **Used for**: Age (regression) & Gender (classification)
- **Strengths**: Lightweight, faster to train, generalizes well
- **Weaknesses**: Less effective with image features

---

## 📊 Results Summary

| Task             | Model | Metric              | Value        |
|------------------|--------|---------------------|--------------|
| Age Prediction   | CNN    | MAE (Test)          | **7.99**     |
| Age Prediction   | MLP    | MAE (Test)          | 12.91        |
| Gender Prediction| CNN    | Accuracy (Test)     | **86.87%**   |
| Gender Prediction| MLP    | Accuracy (Test)     | 85.40%       |

---

## 🧪 Evaluation

### ✅ Confusion Matrices

**CNN Gender**
- True Positives: 308
- False Positives: 72
- Accuracy: 86.87%

**MLP Gender**
- True Positives: 301
- False Positives: 71
- Accuracy: 85.40%

### 📈 Training & Validation Curves

- **CNN Age MAE** shows slight overfitting (val MAE plateaus while train MAE decreases).
- **CNN Gender Accuracy** shows overfitting (train acc ~99%, val ~83%).
- **MLP Age MAE** and **MLP Gender Accuracy** show consistent training with no major overfitting.



