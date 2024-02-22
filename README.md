# Movie-Genre-Classification




## Overview
This project aims to classify movie genres based on their descriptions using machine learning techniques. The dataset includes movie titles, genres, and descriptions.

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Text Preprocessing](#text-preprocessing)
- [Feature Extraction](#feature-extraction)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Genre Prediction](#genre-prediction)
- [Files and Directories](#files-and-directories)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
## Datasets

You can download the datasets used in this project from the following links:

- [Training Data](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)
- [Test Data](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)


## Data
- The training data is sourced from [Dataset Location].
- The test data is sourced from [Dataset Location].
- Basic statistics of the training data are displayed using `pandas`.

## Text Preprocessing
- The `nltk` library is used for text cleaning.
- Text is converted to lowercase, special characters are removed, and stopwords are eliminated.

## Feature Extraction
- TF-IDF vectorization is employed for feature extraction.

## Model Training
- Logistic Regression is utilized for training the classification model.

## Model Evaluation
- Model performance is evaluated using accuracy and classification reports.

## Genre Prediction
- Users can input a movie description, and the trained model predicts the genre.

## Files and Directories
- **train_data.txt**: Training dataset file.
- **test_data.txt**: Test dataset file.
- **main.ipynb**: Jupyter notebook containing the main code.
- **README.md**: Project information and documentation.
- **.gitignore**: Specifies intentionally untracked files that Git should ignore.

## Dependencies
- `pandas`, `matplotlib`, `seaborn`, `nltk`, `scikit-learn`, `wordcloud`.

## Contributing
Feel free to contribute by opening issues or submitting pull requests.

## References
- [ChatGPT by OpenAI](https://www.openai.com/)
- [Kaggle](https://www.kaggle.com/) - Kaggle platform for datasets and competitions
- Many thanks to the coding community on GitHub for inspiration and guidance.


