# Sentiment Analysis with NLTK

## Overview
This Python script performs sentiment analysis on a given set of sentences using the Natural Language Toolkit (NLTK). The sentiment analysis is based on the VADER sentiment analysis tool, which assigns a polarity score to each sentence. The results are presented in a tabular format using the Pandas library.

[![Python Version](https://img.shields.io/badge/Python-3.6%2B-blue)](https://www.python.org/downloads/)
[![NLTK Version](https://img.shields.io/badge/NLTK-3.6-blue)](https://www.nltk.org/)
[![Pandas Version](https://img.shields.io/badge/Pandas-1.0%2B-blue)](https://pandas.pydata.org/)


## Prerequisites
Before running the script, make sure to install the required libraries by executing the following commands:

```bash
pip install pandas nltk tabulate
````

````bash
import nltk
nltk.download('vader_lexicon')
nltk.download('punkt')
nltk.download('stopwords')
````

## Usage
Clone the repository or download the script.
Ensure the required libraries are installed.
Run the script.
## Input
The input data consists of a list of sentences defined in the sentences_array variable. Modify this array to analyze different sets of sentences.

````
sentences_array = [
    "The weather is beautiful today.",
    "I love spending time with my family.",
    # Add more sentences as needed
]
````
## Data Preprocessing
The script performs the following preprocessing steps on the input sentences:

## Removal of non-word characters, numbers, or special symbols.
Tokenization of sentences using NLTK's sent_tokenize.
Removal of stop words using NLTK's English stop words list.
Sentiment Analysis
Sentiment analysis is conducted using the VADER sentiment analysis tool from NLTK. The script calculates the sentiment, positivity percentage, and negativity percentage for each sentence and aggregates the results for the entire set.
