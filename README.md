# NLP applications for Voice of Consumer

All notebooks use pytorch+fast.ai libraries. Here you can find 4 kinds of notebooks:

- Language modeling (starts with a pre-trained model on Wikipedia and updates the word embeddings based on new corpus)
- Sentiment analysis (leverages vocab trained in Language Modeling, then trains a binary sentiment classification model)
- Topic modeling (leverages vocab trained in Language Modeling, then trains a multi-class topic classification model)
- Semantic similarity (leverages vocab trained in Language Modeling, then computes Pearson correlation coefficient against a small labeled dataset)
