# Captioning-of-Articles
Given a news article, caption it. The model is to use a C-LSTM to extract a phrase representation at higher level using CNN and then feed it into LSTM to generate the caption word by word.

Dataset:-
http://goo.gl/forms/5i4KldoWIX

Files:-
signalmedia-1M.jsonl  :  This file has the data in it.
Data.ipynb  :  This file does the conversion of this format into tokens.pkl file
Vocabulary-embedding.ipynb  :  This file takes the data and creates the vocabulary and word embeddings for the text corpus.
Train.ipynb  :  This file builds the model and trains it over the corpus

Execution:
Run all in data.ipynb
Run all in vocabulary-building.ipynb
Run all in train.ipynb

