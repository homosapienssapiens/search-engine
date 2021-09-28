# Search Engine
Search engine with  TF-IDF text vectorization and cosine similarity measure

# Introduction
This project explains how to make a search engine from scratch, bassically a home made google. The engine gets a group of texts, then it tokenizes, normalizes and lemmatizes. The prepared text is vectorized using TF-IDF, a technique to vectorize texts. When the user inputs a query, the engine outputs a list of each text from the more to the least similarity with the given query.

# Goal
To understand the functionality of text vectorization and search engines.

# Siddhartha
Siddharta is one of the most popular novels by the german author Hermann Hesse (1877 - 1962). It tells the story of Siddhartha a spiritually given man who starts his spirirtual journey early in his life, learning from different teachers and looking for wisdom throughout his lifetime. Hesse tells in this book his very own representation of Budda's life.

I decided to use this book for this project because Hesse is my favorite german Author and Siddartha is one of my favorite books. I strongly recommend reading it if you haven't already, no matter the time in your life you are currently in.

The plain text version of the book used in this project was provided by gutemberg.org.
https://www.gutenberg.org/ebooks/2500

# TF-IDF
TF-IDF is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus. For search engines we create vectors of TF-IDF values depending on the total of words in the corpus.

# Cosine similarity measure
There are several techniques to identify the similarity rating of a query in a text. Cosine similarity measure is one of these. It measures the distance of our query vector and a given text vector by their cosine.
