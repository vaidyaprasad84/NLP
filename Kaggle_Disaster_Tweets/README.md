This folder is dedicated to the Kaggle Competition of identifying Disaster Tweets
Herein, I have tested various approaches to identify whether the tweet is disaster or not. 

From a high level POV, I have divide my approaches into various sections:

* Word Embeddings
  * Testing various word embeddings such as count vectorizer, binary vectorizer, TF-IDF, word2vec, doc2vec, GLove
  * using classifications algorithms to classify them into different buckets. 

* Transformers (BERT, BART)
 * Using pre-trained various transformer
 * Fine tuning the entire transformer model architecture on Tweet data
 * Fine tuning only the classification head of the transfomer models
