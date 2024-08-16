# Sarcasm Detection Project

## Overview

This repository contains the report, code, and supplementary documentation for a project focused on detecting sarcasm in text data using machine learning, deep learning, and NLP techniques. The project was completed as part of the CMPUT 651 (Deep Learning for NLP) course at the University of Alberta during the Winter 2021 semester.

## Project Goals

The primary objective of this project was to explore and implement different approaches to sarcasm detection, including:
- Traditional machine learning models (Logistic Regression, Naive Bayes, SVM)
- Deep learning models (BiLSTM, BERT)
- Interpretability techniques (LIME)
- Knowledge graph


## Datasets

This project utilizes two datasets for sarcasm detection:

1. **News Headlines Dataset for Sarcasm Detection**: This dataset contains over 28,000 headlines from various news sources, labeled as either sarcastic or not sarcastic. The dataset can be found on Kaggle [here](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection).

2. **Sarcasm on Reddit Dataset**: This dataset consists of over 32,000 Reddit comments labeled as sarcastic or non-sarcastic, collected from various subreddits. The dataset is available on Kaggle [here](https://www.kaggle.com/datasets/danofer/sarcasm).

Please note that the links to the datasets in the notebooks currently refer to Google Drive paths used during the development phase. To run the notebooks on your local machine, you will need to replace these Google Drive paths with the local paths to the datasets you download from the provided Kaggle links.



## Directory Structure

- **`Report.pdf`**: The final report summarizing the project, including objectives, methodologies, and results.
- **`Notebooks/`**: Contains all the Jupyter notebooks used in the project.
  - `Combined_Models.ipynb`: Notebook applying various models to both datasets, alongside LIME interpretability.
  - **`NewsHeadline/`**: Notebooks related to sarcasm detection in the news headlines dataset.
    - `NewsHeadline_BiLSTM_GloVe.ipynb`: BiLSTM model with GloVe embeddings.
    - `NewsHeadline_EDA.ipynb`: Exploratory data analysis of the news headline dataset.
    - `NewsHeadline_Word2Vec.ipynb`: Word2Vec embeddings used in a deep learning model.
	- `NewsHeadline_Knowledge_Graph.ipynb`: Knowledge Graph of the news headline dataset.
  - **`RedditComments/`**: Notebooks related to sarcasm detection in the Reddit comments dataset.
    - `RedditComments_Logit_NB.ipynb`: TF/IDF vectorizer, Logistic Regression, and Naive Bayes applied to Reddit comments.
    - `RedditComment_BiLSTM.ipynb`:  Exploratory data analysis and BiLSTM model for Reddit comments.


