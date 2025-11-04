# 🎯 Sonar Rock vs Mine Prediction (Logistic Regression)

Welcome! 👋  
This project is a simple Machine Learning model that predicts whether an object detected using **Sonar signals** is a **Rock (R)** or a **Mine (M)**.  
The project is implemented in **Google Colab** using **Python** and **Logistic Regression** as the classification model.

---

## 📘 Overview

Sonar signals are sound waves used to detect underwater objects. By analyzing how these signals reflect back, we can identify what kind of object is present underwater.

In this project:

- The dataset contains **60 numerical features** that represent the strength of sonar signal returns.
- The model predicts:
  - `R` → Rock  
  - `M` → Mine

---

## 🧠 Model Used

We used **Logistic Regression**, a simple yet effective binary classification algorithm.

**Why Logistic Regression?**
- Easy to implement & interpret
- Works well for linearly separable data
- Efficient training and prediction speed

---

## 📂 Project Structure

| File / Folder | Description |
|--------------|-------------|
| `Sonar data.csv` | Dataset used for model training & testing |
| `Sonar Rock vs Mine Pred.ipynb` | Google Colab Notebook with full implementation |
| `README.md` | Project documentation |

Project Repository:  
🔗 **https://github.com/UtkarshJain05/ML_Projects/tree/main/1.%20Sonar%20Rock%20vs%20Mine%20Prediction**

---

## ⚙️ Steps Followed in the Notebook

1. Imported Libraries (NumPy, Pandas, Sklearn)
2. Loaded and explored the dataset
3. Preprocessed data and separated features/labels
4. Split the dataset into **Training** and **Testing** sets
5. Trained the model using **Logistic Regression**
6. Evaluated model accuracy
7. Performed sample prediction

---

## 📈 Model Performance

| Metric | Score |
|-------|-------|
| **Accuracy** | **76.19%** |

> *Accuracy may vary slightly depending on the random state of train-test split.*

---
