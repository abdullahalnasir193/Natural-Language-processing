# Lab 1: Introduction to Natural Language Processing

This lab provides a basic introduction to **Natural Language Processing (NLP)** and demonstrates how to download, load, and explore a textual dataset.

## Objectives

* Understand the basic concept of NLP.
* Explore common NLP applications.
* Become familiar with NLTK.
* Download and load a text dataset.
* Inspect the dataset using Pandas.

## Dataset

This lab uses the **IMDB Dataset of 50K Movie Reviews**, which contains:

* 50,000 movie reviews
* 25,000 positive reviews
* 25,000 negative reviews
* `review` and `sentiment` columns

The dataset is not included in this repository because of its large file size.

It can be downloaded automatically through KaggleHub:

```python
import kagglehub

path = kagglehub.dataset_download(
    "lakshmi25npathi/imdb-dataset-of-50k-movie-reviews"
)

print("Dataset path:", path)
```

Dataset source: [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

## Libraries Used

* Pandas
* NLTK
* KaggleHub

## Files

```text
Lab-01/
├── Lab 1 - Introduction to Natural Language Processing (NLP).ipynb
└── README.md
```

## Installation

```bash
pip install pandas nltk kagglehub
```

## Running the Lab

1. Install the required libraries.
2. Open the Jupyter Notebook.
3. Run the cells in order.
4. KaggleHub will download the dataset automatically.

## Author

**Abdullah Alnasir**
