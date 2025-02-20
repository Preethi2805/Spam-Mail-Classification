# 📧 Spam Mail Detection

Detect spam emails efficiently using **Logistic Regression**! This project demonstrates the power of machine learning in classifying emails as spam or ham. This system achieves high accuracy and ensures reliable predictions by leveraging text preprocessing and feature extraction.

---

## 🛠️ Features
- **Dataset**: 
  - **5,572 email messages** categorized as `spam` or `ham`.  
  - Preprocessing includes dropping irrelevant columns and filling missing values with empty strings.  
  - Labels encoded: `spam = 1`, `ham = 0`.  

- **Feature Extraction**:  
  Utilizes **TF-IDF Vectorizer** to transform text data into numerical features.  
  - Removes stop words.  
  - Converts all text to lowercase for uniformity.  

- **Model Training**:  
  Built using **Logistic Regression** to achieve robust email classification.  
  - **Training Accuracy**: `96.6%`  
  - **Testing Accuracy**: `96.2%`  

- **Predictive System**:  
  Input an email message and the system will classify it as `spam` or `ham`.  

---

## 📊 Workflow
1. **Data Cleaning**:
   - Removed unnecessary columns.
   - Replaced missing values.  
2. **Feature Engineering**:
   - Applied TF-IDF vectorization to convert text into numerical data.  
3. **Model Training**:
   - Trained Logistic Regression on preprocessed data.  
4. **Prediction System**:
   - Deployed a system to classify emails based on their text.  

---

## 📂 Project Structure
```
spam-mail-detection/
├── spam_detection.py       # Main script
├── spam.csv                # Dataset
├── Spam_mail_detection.ipynb # Jupyter Notebook
├── README.md             # Project documentation
```

---

## 🤝 Contributions
Contributions are always welcome! Feel free to fork the repo, raise issues, or submit pull requests.

---
