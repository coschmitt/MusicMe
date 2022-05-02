# MusicMe
The inspiration and explanation behind this project can be found at [MusicMe](https://medium.com/@dgunther613/musicme-7fdb37a6fc97)

Created by: Daniel Gunther, Charlie Schmitt, and Clare Bradley

There are two separate aspects of our project: lyric generation and lyric examination.

## Lyric examination using word embeddings:

To create figures and models for lyric examination:

-Download genre.json found in this repository

-Download song data from this [link](https://www.kaggle.com/datasets/edenbd/150k-lyrics-labeled-with-spotify-valence) (this file was too big to upload to this repository)

-Run the MusicMe Word Word Embedding ipynb

Our model utilizes Google's [Word2Vec](https://code.google.com/archive/p/word2vec/) word embedding model

## Lyric generation:

All required data for running the lyric generation model is in the repo.

The model is a reltivley standard word level NLP for generating text. We used LSTM and Bidirectional LSTM layers for our model architecture.
