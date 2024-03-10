# Sentiment Analysis with NLTK

## Overview
This Python script performs sentiment analysis on a given set of sentences using the Natural Language Toolkit (NLTK). The sentiment analysis is based on the VADER sentiment analysis tool, which assigns a polarity score to each sentence. The results are presented in a tabular format using the Pandas library.

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
