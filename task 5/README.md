🎵 Spotify Lyric Search

Task 5 – NLP & Text Similarity Project

📌 Project Overview

This project implements a lyric-based text identification system that predicts the song title and artist name from a short snippet of song lyrics.

The goal of this task is to demonstrate practical usage of Natural Language Processing (NLP) techniques combined with similarity-based machine learning methods for text search and identification.

📊 Dataset Information

Dataset Name: Spotify Million Song Dataset

Total Records: 57,651

Columns Used:

artist

song

text (lyrics)

The dataset was sourced from Kaggle and contains song lyrics mapped to their respective artists and song titles.

Due to GitHub file size limitations, the complete dataset is not included in this repository.


🛠 Technologies Used

Python

Pandas

Natural Language Processing (NLP)

Scikit-learn

Jupyter Notebook

🧠 Methodology

The lyric identification process follows these steps:

Text Preprocessing

Lowercasing text

Tokenization

Stop-word removal

Removal of punctuation and unwanted characters

Feature Extraction

TF-IDF Vectorization to convert text into numerical feature vectors

Similarity Measurement

Cosine Similarity to measure similarity between lyric snippets

Prediction

The most similar lyric entry is selected to predict the song title and artist

This approach is effective for lyric-based search and text similarity problems.

▶️ Model Usage

The model accepts a short lyric snippet as input and returns:

Predicted Song Title

Predicted Artist

Example Input
she makes me feel fine who could ever believe

Example Output
Predicted Song Title: She's My Kind Of Girl
Predicted Artist: ABBA

📈 Model Evaluation

Prediction performance is demonstrated in the Jupyter Notebook by comparing predicted song titles with actual titles from a validation dataset.

⚙️ Installation & Execution

Open the provided Jupyter Notebook

Ensure the dataset file is available:

Download the full dataset from Kaggle

Or use the provided spotify_sample.csv

Run all notebook cells sequentially

Enter a lyric snippet in the final input cell to test the model

No additional environment setup is required.

📌 Notes

This project uses a similarity-based NLP approach

Emphasis is placed on clarity, correctness, and reproducibility

All work is original and complies with the no-plagiarism policy
