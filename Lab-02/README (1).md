# Lab 2: Text Preprocessing and Regular Expressions

This repository contains the second lab for the Natural Language Processing (NLP) course. The lab introduces essential text preprocessing techniques using Python, regular expressions, NLTK, and spaCy.

## Lab Objectives

By completing this lab, students practice how to:

- Search for patterns using `re.search()` and `re.match()`.
- Extract all matching patterns using `re.findall()`.
- replace text using `re.sub()`.
- Split text using `re.split()`.
- Create reusable regular-expression patterns with `re.compile()`.
- Tokenize sentences and words using NLTK and spaCy.
- Apply stemming and lemmatization to normalize words.
- Extract and count hashtags from a Twitter dataset.

## Main Topics

### Regular Expressions

The lab uses Python's built-in `re` module to identify, extract, replace, and split text based on patterns such as digits, words, and hashtags.

### Tokenization

Tokenization divides text into smaller units such as sentences and words. The lab compares tokenization results from NLTK and spaCy.

### Stemming and Lemmatization

- **Stemming** reduces words to a common stem using rule-based transformations.
- **Lemmatization** converts words to valid dictionary forms while considering their grammatical role.

### Hashtag Analysis

A small text-processing task uses tweets about Apple to:

1. Extract hashtags using regular expressions.
2. Count the total number of hashtag occurrences.
3. Identify the ten most frequently used hashtags.

Dataset: [Apple Twitter Sentiment Texts](https://www.kaggle.com/datasets/seriousran/appletwittersentimenttexts)

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NLTK
- spaCy
- Regular Expressions (`re`)
- KaggleHub

## Installation

Install the required packages:

```bash
pip install pandas nltk spacy kagglehub
python -m spacy download en_core_web_sm
```

Some NLTK resources may also need to be downloaded:

```python
import nltk

nltk.download("punkt")
nltk.download("punkt_tab")
nltk.download("wordnet")
nltk.download("omw-1.4")
```

## Files

- `Lab2_Text_pre_processing_&_regular_expressions-2.ipynb` — notebook containing the explanations, examples, and lab tasks.

## How to Run

1. Open the notebook in Jupyter Notebook or JupyterLab.
2. Select the correct Python kernel.
3. Install any missing dependencies.
4. Run the cells in order from top to bottom.

## Learning Outcome

After completing this lab, students should understand how preprocessing transforms raw text into a cleaner and more structured form suitable for NLP analysis.
