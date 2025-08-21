# 📧 Email Spam Classification using NLP
---

## 📌 Overview
This project builds an **Email Spam Classifier** using **Natural Language Processing (NLP)** and **Machine Learning**.  
It automatically classifies emails into **Spam** or **Ham (Not Spam)** categories based on their content.

---

## 🎯 Objective
- Perform **text preprocessing** (cleaning, stopword removal, stemming/lemmatization).  
- Convert email text into **feature vectors** (Bag-of-Words, TF-IDF).  
- Train ML models (Naive Bayes, Logistic Regression, SVM, Random Forest).  
- Evaluate classification performance using **accuracy, precision, recall, and F1-score**.  

---

## 📂 Dataset
- Common dataset: **SpamAssassin**, **Enron-Spam Dataset**, or **Kaggle Spam Classification Dataset**.  
- Structure:  
  - `ham` → Non-spam emails  
  - `spam` → Spam emails  

---

## 🛠️ Tools & Technologies
- **Python**  
- **NLP Libraries**: NLTK / spaCy  
- **Scikit-learn** (ML models, feature extraction)  
- **Pandas, NumPy** (data handling)  
- **Matplotlib, Seaborn** (visualization)  
- **Jupyter Notebook**

---

## ▶️ **Usage**
Run the Jupyter Notebook to preprocess data, train the model, and test predictions:


## 🔍 Insights


From the exploratory data analysis and model evaluation, we observed:

Word Frequency: Spam emails contain words like free, win, lottery, cash, prize, whereas ham emails use more formal/neutral words.

Message Length: Spam messages are usually shorter but repetitive, while ham emails tend to be longer and more informative.

Stopwords Removal: Removing common stopwords significantly improves accuracy.

Vectorization: TF-IDF features performed better than simple Bag-of-Words.

Algorithm Performance:

Naive Bayes works surprisingly well for spam filtering due to word independence assumption.

SVM and Logistic Regression improve precision and recall.



## ✅ Result



Successfully built a Spam vs Ham classifier using NLP and ML.

Achieved performance (example metrics, replace with your actual results):

Accuracy: ~97%

Precision (Spam): ~95%

Recall (Spam): ~96%

F1-Score: ~95%

Example Predictions:

“🎉 Congratulations! You won $1000 cash, claim now!” → Spam

“Hi, can we reschedule our meeting for tomorrow?” → Ham

Final Outcome: A reliable and efficient Email Spam Detection System that can be extended into real-world mail servers.
