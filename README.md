# TEXT-SUMMARIZATION-TOOL

*COMPANY* : CODTECH IT SOLUTION

*NAME* : CHANDRESH SINGH BHADORIYA

*INTERN ID* :CT04DZ609

*DOMAIN*: ARTIFICIAL INTELIGENCE

*DURATION* : 4 WEEK

*MENTOR* : NEELA SANTOSH

DESCRIPTION : Tool Used:
PyTextRank (with spaCy)

How It Works:
Sentence Segmentation:
The text is divided into sentences.

Text Preprocessing:
Each sentence is tokenized, lemmatized, and cleaned using spaCy NLP pipeline.

Graph Construction:
A similarity graph is constructed where:

Each node is a sentence.

Each edge connects sentences based on semantic similarity.

Scoring with TextRank Algorithm:
Sentences are scored using the TextRank algorithm (like PageRank).
Higher-ranked sentences are considered more important.

Summary Generation:
Top N ranked sentences are selected and returned in order.

PyTextRank is a Python implementation of the TextRank algorithm — a graph-based ranking model for natural language processing. It is primarily used for:

Extractive text summarization (selecting important sentences from the text)

Key phrase extraction

TextRank is similar in concept to Google's PageRank, but it operates on textual units (words, phrases, or sentences) rather than web pages.



