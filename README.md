# Exploring Word Embeddings

Welcome to the "Exploring Word Embeddings" Colab notebook! In this notebook, we'll delve into the fascinating world of word embeddings using GloVe vectors. Word embeddings are powerful representations of words in a numerical format, capturing semantic relationships between words in a dense vector space.

## Introduction

Word embeddings have revolutionized natural language processing tasks by providing a way to represent words as continuous-valued vectors. These vectors encode semantic relationships between words, allowing us to perform various language-related tasks with numerical computations.

## Acknowledgements

In this notebook, we'll be using GloVe vectors for our word embeddings. The GloVe vectors were introduced in the following paper:

Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/pubs/glove.pdf).

Parts of this notebook was done as an exercise in the Coursera course: [Sequence Models](https://www.coursera.org/learn/nlp-sequence-models).

## Notebook Overview

Here's a quick overview of what we'll be exploring in this notebook:

1. **Reading GloVe Vectors**: We'll start by loading pre-trained GloVe vectors from a text file and organizing them into a dictionary.

2. **Cosine Similarity**: We'll explore how to measure the similarity between word vectors using cosine similarity.

3. **Word Analogy Task**: We'll dive into the word analogy task, where we'll complete analogies like "a is to b as c is to ____".

4. **Finding Nearest Neighbors**: We'll find the nearest neighbors of a given word based on Euclidean distances between vectors.

5. **Clustering**: We'll attempt to cluster words based on their embeddings using K-means clustering.
