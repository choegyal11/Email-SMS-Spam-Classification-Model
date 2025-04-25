# Email/SMS Spam Classification Model
This project uses machine learning and natural language processing to classify SMS and email messages as spam or not spam. It aims to reduce digital noise and improve user safety.
**Tools Used:** Python, scikit-learn, pandas, seaborn, nltk  
**Techniques:** TF-IDF Vectorization, Naive Bayes, SVM, Logistic Regression
## 🧠 Process
1. Cleaned text data (lowercase, stop-word removal, lemmatization)
2. Converted text into numerical features using TF-IDF
3. Trained classifiers (Naive Bayes, SVM, Logistic Regression)
4. Evaluated using accuracy, F1 score, and ROC-AUC
5. Visualized results with confusion matrix and classification reports
## ✅ Results
- Naive Bayes achieved 95% accuracy
- The model effectively reduced false positives
- Suitable for integration into basic spam filters
## 🚀 Run It Yourself
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Open `spam_classifier.ipynb` in Jupyter Notebook
4. Run all cells
## 📎 References
- UCI SMS Spam Collection Dataset
- Scikit-learn Documentation
- nltk for text preprocessing
