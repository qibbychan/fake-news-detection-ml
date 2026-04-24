# 🧠 Fake News Detection using Machine Learning

## 📌 Project Overview

This project aims to classify news articles as **Fake** or **Real ** using a Machine Learning approach.
It uses **Natural Language Processing (NLP)** techniques to clean and transform text data before training a classification model.
This project was performed using jupyter notebook. 

---

## ⚙️ Methodology

The workflow of this project is as follows:

1. **Data Collection**

   * Dataset: [WELFake Dataset](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification/data)(from kaggle)

2. **Feature Extraction**

   * TF-IDF (Term Frequency–Inverse Document Frequency)
   * Convert text into numerical vectors

3. **Model Training**

   * Algorithm: Multinomial Naive Bayes

4. **Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Classification Report (Precision, Recall, F1-score)

---

## 📊 Results

* The model is able to classify news articles with good accuracy.
* Performance is evaluated using:

  * Accuracy
  * Precision
  * Recall
  * F1-score
-----

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* NLTK
* Scikit-learn
* Matplotlib & Seaborn

---

## 📁 Project Structure

```
Fake-News-Detection/
│
├── notebook/
│   └── fake_news_detection.ipynb
├── data/
│   └── (dataset not included)
├── README.md
└── requirements.txt
```


## ⚠️ Notes

* Dataset is not included due to size limitations you can get it from kaggle 
---

## 🎯 Future Improvements

* Try other models (Logistic Regression, SVM)
* Improve accuracy with better preprocessing
* Deploy as a web application

