# Internship-Task2-SentimentAnalysis

## 📌 Task Description
This task involves building a **Sentiment Analysis Model** on IMDB reviews.  
The goal is to classify movie reviews as **Positive** or **Negative** using basic preprocessing, feature extraction, and a simple machine learning model.

---

## 📊 Steps Performed
1. **Data Preprocessing**
   - Converted all text to lowercase  
   - Removed special characters and numbers  
   - Removed stopwords (using NLTK)  

2. **Feature Engineering**
   - Used **CountVectorizer** to convert text data into numerical format  

3. **Model Training**
   - Trained a **Logistic Regression** model to classify reviews  

4. **Model Evaluation**
   - Evaluated performance using **accuracy** metric  
   - Achieved classification of reviews into **Positive** or **Negative**  

5. **Custom Prediction**
   - Tested with a sample review to check real-time predictions  

---

## 📂 Files
- `SentimentAnalysis.ipynb` → Jupyter Notebook containing all steps  
- `IMDB Dataset.csv` → Dataset used for training and testing (from Kaggle)  
- `README.md` → Project documentation  

---

## ⚙️ Requirements
Install the required libraries before running the notebook:

```bash
pip install pandas scikit-learn nltk
