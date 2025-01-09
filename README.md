# Word-Level Tokenizer

# About the Project

This model preprocesses textual data, tokenizes it into words, and builds a vocabulary mapping words to unique IDs for further natural language processing tasks.

# Project Implementation and Workflow

**Preprocessing:**
Converts text to lowercase.
Removes punctuation and extra whitespace.

**Tokenization:**
Splits text into individual words (tokens).

**Vocabulary Building:**
Creates a word-to-ID mapping using a frequency-based vocabulary.

**Token Mapping:**
Converts tokenized words into their respective IDs.

**Vocabulary Saving:**
Saves the vocabulary as a .pkl or .csv file for reuse.

# Required Packages to Import

**Pandas:** To handle the dataset.
**Re (Regex):** For text cleaning and tokenization.
**Pickle:** To save the vocabulary in a binary format.

# Install dependencies using:
```bash
pip install pandas
```

