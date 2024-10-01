# NLP Sentiment Analysis Project

This project demonstrates a sentiment analysis pipeline using various natural language processing (NLP) techniques and machine learning models. The primary objective is to classify movie reviews as either **Positive** or **Negative** using the following algorithms:

- Bag of Words (BoW)
- TF-IDF
- N-gram
- Word2Vec
- FastText

Each model is trained to predict sentiment, and a final output is decided by taking the majority vote from the different models.

## Dataset

The dataset used in this project is the [IMDB Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews), consisting of 50,000 movie reviews labeled as **positive** or **negative**.

### Download the Dataset

You can download the dataset from Kaggle:
- [IMDB Dataset on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

Place the dataset in your working directory or Google Drive to use in Colab.

## Models Implemented

1. **Bag of Words (BoW)**: Converts text to feature vectors using word counts.
2. **TF-IDF**: Text vectorization based on term frequency and inverse document frequency.
3. **N-gram**: Uses word pairs (bigrams) as features to capture context.
4. **Word2Vec**: Embedding model that learns vector representations of words based on their usage context.
5. **FastText**: Similar to Word2Vec but captures sub-word information, making it useful for morphologically rich languages.

## How It Works

1. The dataset is preprocessed by tokenizing, lowercasing, and removing stop words.
2. Each model is trained on the preprocessed data.
3. The input text is passed through each model to predict sentiment (positive or negative).
4. The final sentiment is determined by majority voting from the models' predictions.

### File Structure

```bash
├── nlp.py            # Main script for training models and running predictions
├── IMDB Dataset.csv   # Dataset (ensure it's downloaded and available)
└── README.md          # This file



