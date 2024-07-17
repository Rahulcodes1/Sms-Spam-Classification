
# SMS Spam Classification

This project focuses on classifying SMS messages as spam or non-spam (ham) using machine learning techniques. The goal is to build a model that can accurately identify and filter out spam messages, thereby improving the user experience and security of SMS communication.

## Dataset

The dataset used for this project is the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/dataset/228/sms+spam+collection) obtained from the UCI Machine Learning Repository. It contains a collection of SMS messages labeled as either "ham" (non-spam) or "spam". The dataset is provided as a single file named `SMSSpamCollection`.

## Approach

1. **Data Preprocessing**: The text data undergoes preprocessing steps such as lowercase conversion, removal of non-alphabetic characters, tokenization, removal of stopwords, and lemmatization.

2. **Exploratory Data Analysis (EDA)**: Various visualizations are employed to explore the distribution of labels, text length, and relationships between different features.

3. **Modeling**: Several classification models are trained and evaluated using the preprocessed data. The models include:
   - Naive Bayes
   - Support Vector Machine (SVM)
   - XGBoost
   - Random Forest
   - Decision Tree

4. **Evaluation**: The performance of each model is evaluated using metrics such as accuracy, precision, recall, F1 score, confusion matrix, classification report, and ROC curve analysis.

## Results

### Model Performance

| Model           | Accuracy | Precision | Recall | F1 Score |
|-----------------|----------|-----------|--------|----------|
| Naive Bayes     | 0.9803   | 0.9045    | 0.9530 | 0.9281   |
| SVM             | 0.9848   | 0.9925    | 0.8926 | 0.9399   |
| XGBoost         | 0.9767   | 0.9556    | 0.8658 | 0.9085   |
| Random Forest   | 0.9794   | 1.0000    | 0.8456 | 0.9164   |
| Decision Tree   | 0.9758   | 0.9357    | 0.8792 | 0.9066   |


## How to Use

1. Clone the repository:
```bash
    git clone https://github.com/Rahul8959/Covid19_Tracker.git
```
2. Install dependencies:
```bash
    pip install -r Requirements.txt
```
3. Run the Jupyter Notebook `sms_spam_classification.ipynb` to reproduce the project.
