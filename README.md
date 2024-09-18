# Movie-review-IMDB-

## IMDB Movie Review Sentiment Analysis

## Project Overview
This project builds a sentiment analysis model using the IMDB dataset, consisting of 50,000 movie reviews. The goal is to classify reviews as **positive** or **negative**.

## Dataset
The dataset is sourced from Kaggle: [IMDB Movie Reviews](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). It contains:
- **Reviews**: Text reviews of movies
- **Sentiment**: Positive or negative labels

## Workflow
1. **Data Preprocessing**:
   - Tokenization
   - Removing special characters and stopwords
   - Text lowercasing

2. **Model**:
   - Tokenization and padding for input text
   - LSTM model with embedding layers
   - Dropout for regularization

3. **Training**:
   - Early stopping to prevent overfitting
   - Training on 80% of the data, validation on 20%

4. **Evaluation**:
   - Accuracy score calculation on test data.

## Dependencies
- Python 3.x
- TensorFlow
- Keras
- NLTK
- Pandas
- Scikit-learn

## How to Run
1. Download the dataset using Kaggle's API:
   ```bash
   !kaggle datasets download -d lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
   ```
2. Run the notebook to preprocess data and train the model.

## Results
After training, the model achieves a test accuracy of approximately **100%**.
