# Essay-Classification-with-N-Gram-LM
Project for Natural Language Processing Course (COMS 4705) at Columbia University's School of Engineering and Applied Science, Sept 2022

In this project, I built a trigram language model in Python. The main component of the language model is implemented in the class TrigramModel. One important idea behind implementing language models is that the probability distributions are not precomputed. Instead, the model only stores the raw counts of n-gram occurrences and then computes the probabilities on demand. This makes smoothing possible. The two datasets I worked with are available within the hw1_data zip file.

Project Parts:
1. Extracting n-grams from a sentence
2. Counting n-grams in a corpus
3. Raw n-gram probabilities
4. Smoothed probabilities
5. Computing Sentence Probability
6. Perplexity
7. Using the Model for Text Classification
