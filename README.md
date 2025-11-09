# Natural Language Processing (NLP) Project

This repository contains various NLP implementations and techniques using Python and NLTK library.

## Project Structure

```
NLP/
├── BOW/
│   ├── implementation.ipynb      # Bag of Words implementation
│   └── spamhamdata.csv          # Dataset for spam classification
├── Lemmatization/
│   └── practical implementation.ipynb
├── Named Entity Tagging/
│   └── implementation.ipynb
├── Pos Tagging/ 
│   └── practical implementation.ipynb
├── Stemming/
│   └── practical implementation of stemming.ipynb
├── Stop words/
│   └── practical implementation.ipynb 
├── TF-IDF/
│   └── implementation.ipynb
└── Tokenization/
    └── practical implementation.ipynb
```

## Overview

This project implements various NLP concepts and techniques:

1. **Bag of Words (BOW)**
   - Text vectorization implementation
   - Spam classification using BoW
   - Uses spamhamdata.csv dataset

2. **Lemmatization**
   - Word lemmatization using NLTK
   - Reduces words to their base/dictionary form

3. **Named Entity Recognition**
   - Implementation of NER to identify entities like person names, organizations, locations etc.

4. **Parts of Speech (POS) Tagging**
   - Grammatical tagging of words
   - Identifies nouns, verbs, adjectives etc.

5. **Stemming**
   - Word stemming implementation
   - Reduces words to their root/stem form

6. **Stop Words**
   - Handling and removal of stop words
   - Text preprocessing

7. **TF-IDF**
   - Term Frequency-Inverse Document Frequency implementation
   - Text vectorization using TF-IDF weights

8. **Tokenization**
   - Text tokenization into sentences and words
   - Using NLTK's tokenization utilities

## Requirements

- Python 3.x
- NLTK
- Pandas
- NumPy
- Jupyter Notebook

## Getting Started

1. Clone this repository
2. Install required dependencies:
```bash
pip install nltk pandas numpy jupyter
```
3. Download required NLTK data:
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```
4. Open desired notebook in Jupyter to view implementations

## Usage

Each notebook contains practical implementations with examples. The notebooks are self-contained with necessary explanations and code.

To run a specific implementation:
1. Navigate to the respective folder
2. Open the `.ipynb` file in Jupyter Notebook
3. Run cells sequentially to see the implementation

## Dataset

The spam classification example uses `spamhamdata.csv` which contains labeled text messages for spam detection.

## License

This project is for educational purposes. Feel free to use and modify as needed.