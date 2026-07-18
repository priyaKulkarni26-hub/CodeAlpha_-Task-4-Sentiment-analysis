# CodeAlpha_-Task-4-Sentiment-analysis
# 📝 Task 4 – Sentiment Analysis using NLP

## 📌 Project Overview

This project performs **Sentiment Analysis** on Amazon product reviews using **Natural Language Processing (NLP)** and **Machine Learning**. The model classifies reviews into **Positive**, **Negative**, and **Neutral** sentiments. It also performs **Emotion Detection** and visualizes the results using charts.

This project was developed as part of a **Data Analytics Internship**.

---

## 🎯 Objectives

- Analyze customer reviews using NLP.
- Classify reviews into Positive, Negative, and Neutral sentiments.
- Detect emotions from review text.
- Visualize sentiment distribution.
- Evaluate model performance.
- Generate business insights for marketing and product improvement.

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TextBlob
- NRCLex (Emotion Detection)
- Regular Expressions (re)

---

## 📂 Dataset

**Dataset:** Amazon Product Reviews

Columns used:
- Review
- Rating

The sentiment labels are generated from ratings:
- ⭐⭐⭐⭐⭐ / ⭐⭐⭐⭐ → Positive
- ⭐⭐⭐ → Neutral
- ⭐⭐ / ⭐ → Negative

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Text Preprocessing
5. Sentiment Labeling
6. Feature Extraction (CountVectorizer)
7. Train-Test Split
8. Train Naive Bayes Model
9. Predict Sentiment
10. Evaluate Accuracy
11. Classification Report
12. Emotion Detection
13. Data Visualization
14. Business Insights

---

## 📈 Visualizations

The project includes:

- Bar Chart of Sentiments
- Pie Chart of Sentiments
- Emotion Distribution Chart

---

## 🤖 Machine Learning Model

Algorithm Used:

- Multinomial Naive Bayes

Feature Extraction:

- CountVectorizer

Evaluation Metrics:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report

---

## 😊 Emotion Detection

The project detects emotions such as:

- Joy 😊
- Trust 🤝
- Fear 😨
- Anger 😠
- Sadness 😢
- Surprise 😲
- Anticipation 🙂
- Disgust 🤢

---

## 📊 Sample Output

Accuracy

```
Accuracy: 91%
```

Classification Report

```
Precision
Recall
F1-Score
Support
```

Sentiment Distribution

```
Positive : 65%
Neutral  : 18%
Negative : 17%
```

---

## 💡 Business Insights

The sentiment analysis can help businesses to:

- Understand customer satisfaction.
- Identify common customer complaints.
- Improve product quality.
- Enhance customer experience.
- Support marketing strategies.
- Monitor brand reputation.

---

## 📁 Project Structure

```
Task4-Sentiment-Analysis/
│
├── amazon_reviews.csv
├── Task4_Sentiment_Analysis.ipynb
├── README.md
├── requirements.txt
└── screenshots/
    ├── bar_chart.png
    ├── pie_chart.png
    └── emotion_chart.png
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Task4-Sentiment-Analysis.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn textblob nrclex
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Task4_Sentiment_Analysis.ipynb
```

Run all cells.

---

## 📦 Requirements

```
pandas
numpy
matplotlib
scikit-learn
textblob
nrclex
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 📚 Learning Outcomes

After completing this project, you will understand:

- Text preprocessing
- Natural Language Processing (NLP)
- Sentiment Analysis
- Emotion Detection
- Machine Learning Classification
- Data Visualization
- Model Evaluation

---

## 👩‍💻 Author

**Priya Kulkarni**

MCA Student | Aspiring Data Analyst

GitHub: https://github.com/priyaKulkarni26-hub

---

## ⭐ Acknowledgements

- Scikit-learn
- Pandas
- Matplotlib
- TextBlob
- NRCLex
- Amazon Reviews Dataset

---

## 📜 License

This project is created for educational and internship purposes.
