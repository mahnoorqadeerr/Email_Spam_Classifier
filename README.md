# Email Spam Classifier

This project is a basic machine learning model that classifies emails as **spam** or **not spam** using Python and scikit-learn. It demonstrates text preprocessing, feature extraction, and binary classification using logistic regression.

## Project Overview

- **Dataset**: Public spam email dataset with labeled messages
- **Goal**: Predict whether an email is spam based on its content
- **Accuracy Achieved**: [Insert final accuracy here, e.g., 95.2%]

## Workflow Summary

1. **Data Preprocessing**
   - Removed punctuation and special characters
   - Converted text to lowercase
   - Removed stopwords using NLTK

2. **Label Mapping**
   - Converted labels to binary format: `1 = spam`, `0 = not spam`

3. **Feature Extraction**
   - Used `TfidfVectorizer` to convert email text into numerical features

4. **Model Training**
   - Trained a `LogisticRegression` model using train-test split
   - Evaluated using accuracy score and confusion matrix

## Results

- **Accuracy**: `[Insert your model’s accuracy here]`
- **Confusion Matrix**: Visualized using Seaborn

## Technologies Used

- Python
- Pandas, NumPy
- scikit-learn
- NLTK
- Matplotlib, Seaborn

## How to Run

```bash
# Install dependencies
!pip install pandas numpy scikit-learn nltk

# Upload dataset
from google.colab import files
uploaded = files.upload()

# Run all cells in the notebook

