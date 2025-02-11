# Sentiment Analysis on Amazon Reviews

## Introduction
This project focuses on **Sentiment Analysis** using Natural Language Processing (NLP) and Machine Learning techniques, the model classifies customer reviews as **Positive, Neutral, or Negative**.

## Features
- Data preprocessing: text cleaning, tokenization, and lemmatization
- Feature extraction using **TF-IDF Vectorization**
- Model training with multiple classifiers (Logistic Regression, SVM, Decision Tree, etc.)
- Hyperparameter tuning using GridSearchCV
- Data balancing using **SMOTE**
- Evaluation using **Confusion Matrix** and classification reports

## Tech Stack
- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, NLTK, TextBlob
- **Machine Learning Models**: Logistic Regression, SVM, Decision Tree, Random Forest, Naïve Bayes, KNN
- **Feature Engineering**: TF-IDF Vectorization, Label Encoding

## Installation & Setup
### Prerequisites
Ensure you have Python installed along with the required dependencies:
```sh
pip install pandas numpy matplotlib nltk textblob scikit-learn imbalanced-learn wordcloud
```

### Running the Project
1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   cd Megathon
   ```
2. **Run the script:**
   ```sh
   python sentiment_analysis.py
   ```

## Model Training
The script performs the following steps:
1. **Load & Preprocess Data** (handle missing values, clean text, tokenize, lemmatize)
2. **Feature Extraction** (TF-IDF Vectorization)
3. **Data Balancing** (SMOTE to handle class imbalance)
4. **Model Training** (various classifiers tested)
5. **Hyperparameter Tuning** (GridSearchCV for best parameters)
6. **Evaluation** (accuracy score, classification report, confusion matrix)

## Results
- **Best model:** Logistic Regression with **95% accuracy** after hyperparameter tuning.
- **Challenges:** Imbalanced dataset, improved using **SMOTE resampling**.

## Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-branch`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature-branch`)
5. Create a Pull Request
