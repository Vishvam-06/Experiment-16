# Experiment-16

## Aim
To implement and understand fundamental Natural Language Processing (NLP) techniques for text preprocessing and analysis using the Python Natural Language Toolkit (NLTK) library.

## Theory
Natural Language Processing (NLP) involves the interaction between computers and human language. Before text data can be fed into machine learning or deep learning models, it must be cleaned and preprocessed. This experiment covers several core text preprocessing techniques:

Tokenization: The process of breaking down a stream of text into smaller, meaningful units called tokens (words or sentences). It is the foundational step in text processing.

Stop Word Removal: The elimination of commonly used grammatical words (such as "is", "the", "a", "and") that carry very little domain-specific information. This helps reduce the dataset's dimensionality and allows the focus to remain on meaningful keywords.

Stemming: A crude, rule-based heuristic process that chops off the ends of words to reduce them to their base or root form (e.g., "studies" becomes "studi"). It is computationally fast but may result in non-dictionary words.

Lemmatization: A more sophisticated approach that uses vocabulary and morphological analysis to return the base, valid dictionary form of a word, known as the lemma (e.g., "studies" becomes "study").

Part-of-Speech (POS) Tagging: The process of categorizing words in a text corresponding to a particular part of speech (like noun, verb, adjective) based on its definition and context.
Word Frequency Count: Analyzing the distribution of words within a text document to identify the most common or significant terms using frequency distributions.



Topics Covered in the Notebook
Downloading essential NLTK corpora and models (punkt, stopwords, wordnet, averaged_perceptron_tagger)
Word and Sentence Tokenization (word_tokenize, sent_tokenize)
Filtering words using the NLTK English stop words list
Word Stemming utilizing the PorterStemmer
Word Lemmatization utilizing the WordNetLemmatizer
POS Tagging utilizing pos_tag
Calculating and visualizing word frequencies using FreqDist

## Conclusion
Through this experiment, essential NLP text preprocessing techniques were successfully implemented. These fundamental operations—tokenization, noise removal (stop words), text normalization (stemming and lemmatization), and linguistic analysis (POS tagging)—are critical first steps in structuring raw text data.
