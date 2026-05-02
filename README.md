🧠** Fake News Detection using Machine Learning**
A machine learning pipeline that classifies news articles as Real or Fake using Natural Language Processing (NLP) techniques.

📌 **Problem Statement**
Misinformation spreads faster than ever online. This project explores whether a machine learning model can reliably distinguish fake news from real news based on article text alone — using only classical NLP techniques (no deep learning required).

⚙️ **Workflow**
StepDescription1. Data CollectionWELFake Dataset from Kaggle (~72,000 news articles)2. Text PreprocessingLowercasing, stopword removal, stemming via NLTK3. Feature ExtractionTF-IDF vectorization (text → numerical vectors)4. Model TrainingMultinomial Naive Bayes classifier5. EvaluationAccuracy, Precision, Recall, F1-score, Confusion Matrix

📊** Model Results**
MetricScoreAccuracy(Accuracy: 85.45%, Precision=0.85, Recall=0.85, F1 score= 0.85)
Predicted Real 
(0)Predicted Fake ✅ 826 correct❌ 151 wrongActual Fake
(1)Actual Real     ❌ 140 wrong✅ 883 correct

- 826 real news articles correctly identified as real
- 883 fake news articles correctly identified as fake
- 151 real articles wrongly flagged as fake (false positives)
- 140 fake articles missed as real (false negatives)

🛠️ Tech Stack

Language: Python 3
Libraries: Pandas, NumPy, NLTK, Scikit-learn, Matplotlib, Seaborn
Environment: Jupyter Notebook


📁 Project Structure
fake-news-detection-ml/
│
├── fake-news-detection-ml.ipynb   # Main notebook (EDA + model training + evaluation)
└── README.md

📥 Dataset not included due to file size. Download the WELFake Dataset from Kaggle and place it in the same directory before running.


🚀 How to Run
bash# 1. Clone the repo
git clone https://github.com/qibbychan/fake-news-detection-ml.git
cd fake-news-detection-ml

# 2. Install dependencies
pip install pandas numpy nltk scikit-learn matplotlib seaborn jupyter

# 3. Download NLTK data (run once in Python)
import nltk
nltk.download('stopwords')

# 4. Launch Jupyter and open the notebook
jupyter notebook

🔮 Future Improvements

 Test additional models: Logistic Regression, SVM, Random Forest
 Experiment with n-gram features for better context capture
 Deploy as a simple web app using Streamlit or Flask


🏷️ Topics
machine-learning nlp fake-news-detection python scikit-learn jupyter-notebook tfidf naive-bayes
