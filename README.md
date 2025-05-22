#  News Category Classifier using Machine Learning

This project is a multiclass text classification model trained on real-world news headlines and descriptions to automatically predict their category out of 40+ possible topics. The dataset is sourced from HuffPost and includes over 200,000 articles.

## Project Overview

- Built a Logistic Regression model to classify news headlines into categories like Politics, Entertainment, Business, Sports, and more.
- Used TF-IDF vectorization for feature extraction from text data.
- Achieved ~43% accuracy with insightful per-class precision, recall, and F1-score metrics.
- Highlighted challenges like class imbalance and multi-label overlap.

## Dataset

- Format: JSON
- Columns used: `headline`, `short_description`, `category`
- Categories: 41 unique classes

## Tech Stack

- Python (pandas, NumPy)
- Scikit-learn (Logistic Regression, TF-IDF, LabelEncoder)
- Google Colab

## Model Performance

- Accuracy: ~43%
- Precision, Recall, F1-score breakdown across all classes
- Stronger results for high-frequency categories like “Politics” and “Entertainment”

## Future Improvements

- Try SVM, RandomForest, or Naive Bayes
- Use class weights or SMOTE to deal with imbalance
- Add deep learning models like BERT (Hugging Face Transformers)

## 📂 Project Structure

```bash
.
├── News_Category_Classifier_AI_Project.ipynb   # Main notebook
├── README.md                                   # This file
