# Sarcasm Detection Using NLP

This project demonstrates a Natural Language Processing (NLP) pipeline for detecting sarcasm in news headlines. It utilizes various machine learning algorithms to classify headlines as either sarcastic or non-sarcastic.

## Dataset

The project uses the "Sarcasm in News Headlines" dataset, stored in `sarcasm.json`. This dataset contains news headlines labeled with a binary variable indicating whether the headline is sarcastic (1) or not (0).

## Features

- **Data Preprocessing**: Cleaning text by removing URLs, special characters, and converting to lowercase.
- **Tokenization & Lemmatization**: Using NLTK to process text data.
- **Exploratory Data Analysis (EDA)**: Visualizing class distribution, word clouds, and text length statistics.
- **Model Training**: Implementing and comparing multiple models:
  - Naive Bayes
  - Logistic Regression
  - Random Forest
- **Evaluation**: Comparing models based on accuracy and other metrics.

## Dependencies

To run this project, you will need the following Python libraries:

- python (>=3.6)
- pandas
- numpy
- matplotlib
- seaborn
- wordcloud
- nltk
- scikit-learn

## Setup and Usage

1. Clone the repository to your local machine.
2. Ensure you have the required datasets and libraries installed.
3. Open the Jupyter Notebook `sarcasm_detection.ipynb`.
4. Run the cells sequentially to execute the pipeline.

## Results

According to the experiment results:

- **Best Performing Model**: Naive Bayes
- **Naive Bayes Accuracy**: ~79.0%
- **Logistic Regression Accuracy**: ~78.6%
- **Random Forest Accuracy**: ~76.4%

The model identified words such as "man", "nation", "area", and "report" as significant indicators of sarcasm in this dataset.

## Project Structure

- `sarcasm_detection.ipynb`: The main Jupyter Notebook containing the code and analysis.
- `sarcasm.json`: The dataset file.
- `results.json`: A JSON file containing the summary of the model performance and predictions.
- `README.md`: This file.
