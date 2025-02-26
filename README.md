# Sentiment Analysis on Amazon Alexa Reviews

This project performs sentiment analysis on a dataset of Amazon Alexa product reviews. The goal is to understand customer sentiment based on their reviews and ratings.

## Dataset
link: https://www.kaggle.com/datasets/sid321axn/amazon-alexa-reviews

The dataset contains the following columns:
- **rating**: The rating given by the user (1 to 5).
- **date**: The date of the review.
- **variation**: The variation of the product reviewed.
- **verified_reviews**: The text of the review.
- **feedback**: Binary feedback (1 for positive, 0 for negative).

## Libraries Used

- **pandas**: For data manipulation and analysis.
- **re**: For regular expressions, useful for text processing.
- **nltk**: Natural Language Toolkit, used for text processing tasks like tokenization and stemming.
- **numpy**: For numerical operations.
- **matplotlib** and **seaborn**: For data visualization.

## Steps

1. **Importing Libraries**: Import necessary libraries for data manipulation, text processing, and visualization.
2. **Mounting Google Drive**: Access the dataset stored in Google Drive.
3. **Loading the Dataset**: Load the dataset from a TSV file.
4. **Exploring the Dataset**: Understand the structure and content of the dataset.
5. **Data Visualization**: Create visualizations to understand the distribution of data.
6. **Text Preprocessing**: Perform tokenization, stopwords removal, and stemming.
7. **Sentiment Analysis**: Classify the text as positive, negative, or neutral.
8. **Visualizing Sentiment**: Show the distribution of sentiments across different ratings or product variations.

## Potential Improvements

1. **Feature Engineering**: Create new features from the existing data.
2. **Advanced Sentiment Analysis**: Use machine learning or deep learning models for more accurate sentiment analysis.
3. **Interactive Visualizations**: Use libraries like `plotly` for interactive visualizations.

## How to Run

1. Clone the repository.
2. Open the Jupyter Notebook in Google Colab or any Jupyter environment.
3. Ensure the dataset is accessible (either locally or via Google Drive).
4. Run the notebook cells sequentially to perform the analysis.
