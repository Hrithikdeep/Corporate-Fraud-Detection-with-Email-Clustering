# 🕵️ Corporate Fraud Detection using Email Clustering

This project focuses on detecting potential corporate fraud patterns by analyzing internal email communication using unsupervised machine learning. The dataset includes thousands of email messages, and clustering techniques are applied to uncover hidden structures and unusual communication behaviors.

---

## 📌 Project Overview

- **Objective**: Cluster internal email messages to identify suspicious patterns, potential fraud-related discussions, and communication outliers.
- **Technique**: Unsupervised Machine Learning using TF-IDF vectorization and KMeans clustering.
- **Dataset**: `split_emails.csv` from [Email Clustering GitHub Repo](https://github.com/abhishek-kathuria/Email-Clustering)
- **Tools Used**: Python, Pandas, Scikit-learn, Seaborn, Matplotlib, WordCloud

---

## 📁 Dataset Information

| Column Name | Description |
|-------------|-------------|
| `file`      | Path of the original email file |
| `message`   | Full text content of the email |

---

## 🔍 Workflow

1. **Data Loading**: Load the dataset and inspect structure.
2. **Data Cleaning**: Remove unnecessary columns, duplicates, and handle missing values.
3. **Feature Engineering**: Create an `email_length` column to analyze message size.
4. **EDA (Exploratory Data Analysis)**:
   - Distribution of email lengths
   - WordCloud of most frequent words
   - Longest emails for outlier detection
5. **Text Vectorization**:
   - TF-IDF vectorizer applied to transform text into numerical features.
6. **Clustering**:
   - KMeans clustering to group similar emails.
   - WordCloud per cluster for interpretation.
7. **Interpretation**:
   - Analyze clusters for suspicious or fraud-like communication patterns.

---

## 📊 Visualizations Included

- Histogram of email lengths
- WordCloud of full text
- WordCloud per cluster
- Most frequent email lengths

---

## 🧠 Key Learnings

- TF-IDF and KMeans are powerful for analyzing text without labels.
- Unsupervised learning can surface meaningful patterns even in unstructured data.
- Communication clustering can assist in internal audit and fraud detection.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/Corporate-Fraud-Detection.git
