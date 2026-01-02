Lyrics-Based Song Identification (ML)
-----------------------------------------

Overview
---------

This project is a Machine Learning and Natural Language Processing (NLP) based system that identifies the song title and artist from a given snippet of song lyrics. The model uses text preprocessing, TF-IDF vectorization, and cosine similarity to retrieve the most relevant song.

Objective
----------

Given a small text or lyric snippet, predict the most likely song and artist from the dataset.

Technologies Used
------------------

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK

Approach
---------

1. Generated a large lyrics dataset with song titles and artists.
2. Applied text preprocessing (lowercasing, stop-word removal).
3. Converted lyrics into TF-IDF vectors.
4. Used cosine similarity to match input lyrics with stored songs.
5. Evaluated model performance using Top-K accuracy.

Results
--------
- Achieves high Top-K accuracy when full lyrics are provided.
- Performance decreases with shorter lyric snippets, reflecting real-world ambiguity.
- Confirms correctness of the similarity-based retrieval approach.

How to Run
------------
1. Install dependencies:
     pip install -r requirements.txt
2. Open and run the Jupyter Notebook:
     spotify_lyric_search.ipynb


Use Case
---------

This project demonstrates how NLP techniques can be used in music search engines to identify songs based on textual input such as lyrics.

Author
-------
Arijit Gupta

