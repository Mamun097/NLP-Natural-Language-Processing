# Sentiment Analysis Model

This project demonstrates a sentiment analysis model using Natural Language Processing (NLP) techniques. This model can decide whether a review is positive or negative. The model is built using Python and various libraries such as Numpy, Pandas, NLTK, and Scikit-learn.

## Process Flow

1. **Importing Libraries**: Import necessary libraries for data manipulation, preprocessing, and model building.
2. **Importing Dataset**: Load the dataset from a TSV file.
3. **Data Preprocessing**: Clean and preprocess the text data.
4. **Data Transformation**: Convert text data into numerical features using CountVectorizer.
5. **Splitting Dataset**: Split the dataset into training and testing sets.
6. **Model Fitting**: Train a Naive Bayes classifier on the training data.
7. **Performance Analysis**: Evaluate the model's performance using a confusion matrix and accuracy score.

## Key Points

- **Libraries Used**: Numpy, Pandas, NLTK, Scikit-learn
- **Dataset**: The dataset is a TSV file containing text reviews and their corresponding sentiment labels.
- **Text Preprocessing**: Includes removing non-alphabetic characters, converting to lowercase, removing stopwords (except 'not'), and stemming.
- **Feature Extraction**: Using CountVectorizer to convert text data into numerical features.
- **Model**: Naive Bayes classifier is used for sentiment classification.

## How to Run the Code

1. **Clone the Repository**: Clone this repository to your local machine.
    ```bash
    git clone https://github.com/Mamun097/NLP-Natural-Language-Processing
    cd Sentiment-Analysis
    ```

2. **Install Dependencies**: Install the required libraries using pip.
    ```bash
    pip install numpy pandas nltk scikit-learn
    ```

3. **Download NLTK Data**: Download the necessary NLTK data.
    ```python
    import nltk
    nltk.download('stopwords')
    ```

4. **Run the Jupyter Notebook**: Open and run the `sentiment_analyzer.ipynb` notebook.
    ```bash
    jupyter notebook sentiment_analyzer.ipynb
    ```

5. **Follow the Steps**: Execute each cell in the notebook sequentially to preprocess the data, train the model, and evaluate its performance.

## Conclusion

This project provides a basic framework for building a sentiment analysis model using NLP techniques. By following the steps outlined in the Jupyter notebook, you can preprocess text data, train a classifier, and evaluate its performance.

For any questions or issues, please open an issue in the repository.