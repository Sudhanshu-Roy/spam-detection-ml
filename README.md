# 📧 Spam Email Detection using Machine Learning

This project builds an end-to-end spam email detection system using 
Natural Language Processing (NLP) and Machine Learning techniques to classify messages as **Spam** or **Not Spam (Ham)**.

---

## 🚀 Features
- Text preprocessing and cleaning
- TF-IDF feature extraction
- Logistic Regression and Naive Bayes models
- Model evaluation using precision, recall, and F1-score
- Custom email testing for real-world usage

---

## 🛠️ Technologies Used
- Python  
- Scikit-learn  
- Pandas, NumPy  
- NLTK  
- TF-IDF Vectorizer  

---

## 📊 Dataset
The dataset contains categorized email messages labeled as:
- **Ham** (Not Spam)
- **Spam**

Below is the bar graph showing the distribution of spam and ham messages in the dataset:

<img width="580" height="479" alt="Category Distribution" src="https://github.com/user-attachments/assets/fd1c0669-ec6c-4eaa-b851-4626269e4362" />

---

## 📉 Model Evaluation

### Logistic Regression – Confusion Matrix
<img width="579" height="448" alt="Logistic Regression Confusion Matrix" src="https://github.com/user-attachments/assets/da268d73-1cbe-4087-b8f8-664345eb2055" />

### Naive Bayes – Confusion Matrix
<img width="579" height="448" alt="Naive Bayes Confusion Matrix" src="https://github.com/user-attachments/assets/23f947c9-96e8-43c7-bed3-8630442505d6" />

---

## How to Run

1. Clone the repository
```bash
git clone https://github.com/Sudhanshu-Roy/spam-detection-ml.git
```

2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Run the notebooks in order

## Result

The trained models achieve high spam recall, making the system reliable for real-world spam detection where minimizing false negatives is critical.
