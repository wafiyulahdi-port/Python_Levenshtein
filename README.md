# Python_Levenshtein
This project demonstrates the implementation of Levenshtein Distance for basic spelling correction and similarity measurement between strings. This is 2025 project

The notebook contains two main components:
1. Manual Levenshtein Distance Calculation
The project begins with a step-by-step, matrix-based implementation of the Levenshtein algorithm.
This includes:
* Initializing the edit-distance matrix
* Computing insertions, deletions, and substitutions
* Calculating the minimum edit operations needed to transform one string into another

2. Spelling Correction Using Tokenized Vocabulary
A more advanced implementation uses:
* NLTK tokenization
* A dataset of sentences to build a unique vocabulary
* A custom Levenshtein function
* A simple rule-based spelling correction mechanism

The spelling correction process works by:
* Tokenizing the input sentence
* Comparing each word to the vocabulary
* Selecting the closest match based on minimum edit distance
* Replacing misspelled words while preserving digits
