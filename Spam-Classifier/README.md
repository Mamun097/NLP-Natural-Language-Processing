# Spam Classifier

This project is a simple spam classifier using a Naive Bayes classifier. It processes a dataset of SMS messages, cleans and preprocesses the text, creates a Bag of Words model, and then trains a Naive Bayes classifier to classify messages as spam or not spam.

## Dataset

The dataset used is the "SMSSpamCollection" dataset, which contains SMS messages labeled as "spam" or "ham" (not spam).
Download the dataset from here: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

## Methods Used

1. **Data Cleaning and Preprocessing**:
   - Removing non-alphabetic characters.
   - Converting text to lowercase.
   - Removing stopwords.
   - Stemming words using the Porter Stemmer.

2. **Feature Extraction**:
   - Creating a Bag of Words model using `CountVectorizer`.

3. **Model Training**:
   - Splitting the dataset into training and testing sets.
   - Training a Naive Bayes classifier `MultinomialNB`.

4. **Model Evaluation**:
   - Generating a confusion matrix.
   - Calculating the accuracy of the model.

## How to Run

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries: `pandas`, `nltk`, `scikit-learn`

### Installation

1. Clone the repository or download the project files.
2. Install the required libraries using pip:

```sh
pip install pandas nltk scikit-learn
```

### Running the Classifier
1. Open the spam_classifier.ipynb file in Jupyter Notebook.
2. Run each cell sequentially to execute the code.