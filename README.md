# Taskdatascience
#  Consumer Complaint Text Classification

This project is part of **Kaiburr Assessment - Task 5**, where we build a lightweight machine learning model to classify customer complaints filed with the U.S. Consumer Financial Protection Bureau (CFPB).

---

##  What’s the Goal?

We aim to automatically classify each complaint into one of the following categories:

- `0`: Credit reporting, repair, or other  
- `1`: Debt collection  
- `2`: Consumer Loan  
- `3`: Mortgage  

---

## What We Did

### 1.Exploratory Data Analysis (EDA)
- Looked at how many complaints fall into each category.
- Checked complaint length and removed rows with missing or invalid entries.

### 2.Text Preprocessing
- Lowercased the text, removed special characters and stopwords.
- Converted the clean text into numerical features using **TF-IDF** vectorization.

### 3. Model Selection
- Used **Logistic Regression**, **Support Vector Machine (SVM)**, and **Naive Bayes** for classification.
- These models were chosen for being lightweight, fast, and effective for text-based tasks.
- Compared their performance and selected the best based on accuracy and resource efficiency.
 the model lightweight.

### 4.Model Evaluation
- Evaluated the model using **Accuracy**, **Precision**, **Recall**, **F1-score**, and **Confusion Matrix**.

### 5.Predictions
- Created a function that can take any new complaint text and return the predicted category.

---

## Model Performance

- **Algorithm Used**: Logistic Regression  
- **Accuracy Achieved**: ~97% (may vary slightly)
- Includes detailed performance metrics for each category.

---

## Dataset Info

- **Source**: [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database)  
- **Format**: CSV (loaded from URL)  
- Focused only on the relevant categories listed above.

---

## Want to Try It Yourself?

### Run on Google Colab

1. Open the provided `.ipynb` notebook in [Google Colab](https://colab.research.google.com/).
2. If any packages are missing, install them when prompted.
3. Run all the cells to explore the data, train the model, and test predictions.

![Screenshots](screenshots/)
