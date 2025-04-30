# 🧠 NLP Text Preprocessing

This project demonstrates essential text preprocessing techniques for Natural Language Processing (NLP) using Python, NLTK, and other common NLP libraries. It includes step-by-step notebooks and a dataset for practical exploration.

## 📂 Notebooks

### **Preprocessing**

| **Topic**              | **Description**                                      | **File**                                               |
|------------------------|------------------------------------------------------|--------------------------------------------------------|
| Lowercase              | Convert text to lowercase                            | [`lowercase.ipynb`](preprocessing/lowercase.ipynb)     |
| Regex                  | Clean text using regular expressions                 | [`regex.ipynb`](preprocessing/regex.ipynb)             |
| Tokenization           | Split text into tokens                               | [`tokenization.ipynb`](preprocessing/tokenization.ipynb) |
| Stopwords              | Remove common stopwords                              | [`stopwords.ipynb`](preprocessing/stopwords.ipynb)     |
| Stemming               | Apply stemming algorithms                            | [`stemming.ipynb`](preprocessing/stemming.ipynb)       |
| Lemmatization         | Perform lemmatization                                | [`lemmatization.ipynb`](preprocessing/lemmatization.ipynb) |
| N-gram                 | Generate unigrams, bigrams, and trigrams             | [`n-gram.ipynb`](preprocessing/n-gram.ipynb)           |

### **Classification**

| **Topic**              | **Description**                                      | **File**                                               |
|------------------------|------------------------------------------------------|--------------------------------------------------------|
| Named Entity Recognition (NER) | Extract named entities from text               | [`ner.ipynb`](classification/ner.ipynb)               |
| Part-of-Speech (POS) Tagging | Label words with their part-of-speech tags         | [`pos-tagging.ipynb`](classification/pos-tagging.ipynb) |

### **Vectorization**

| **Topic**              | **Description**                                      | **File**                                               |
|------------------------|------------------------------------------------------|--------------------------------------------------------|
| Bag of Words (BoW)     | Vectorization using Bag of Words                     | [`bag-of-word.ipynb`](vectorization/bag-of-word.ipynb) |
| TF-IDF                 | Vectorization using TF-IDF                           | [`tf-idf.ipynb`](vectorization/tf-idf.ipynb)           |

### **Sentiment Analysis**

| **Topic**              | **Description**                                      | **File**                                               |
|------------------------|------------------------------------------------------|--------------------------------------------------------|
| Pre-trained Transformer | Sentiment analysis using pre-trained transformer models | [`pre-trained-transformer.ipynb`](sentiment/pre-trained-transformer.ipynb) |
| Rule-based             | Rule-based sentiment analysis                        | [`rule-based.ipynb`](sentiment/rule-based.ipynb)       |

### **Topic Modeling**
| **Topic**              | **Description**                                      | **File**                                               |
|------------------------|------------------------------------------------------|--------------------------------------------------------|
| LDA                    | Topic modeling using Latent Dirichlet Allocation    | [`lda.ipynb`](topic-modeling/lda.ipynb)                |
| LSA                    | Topic modeling using Latent Semantic Analysis     | [`lsa.ipynb`](topic-modeling/lsa.ipynb)                |

### **Full Pipeline**

| **Topic**              | **Description**                                      | **File**                                               |
|------------------------|------------------------------------------------------|--------------------------------------------------------|
| TripAdvisor Reviews    | Full pipeline on real-world TripAdvisor dataset      | [`text-processing-trip-advisor.ipynb`](text-processing-trip-advisor.ipynb) |

### **Transformers**

| **Topic**              | **Description**                                      | **File**                                               |
|------------------------|------------------------------------------------------|--------------------------------------------------------|
| Book Reviews           | Sentiment analysis using transformer models on book reviews | [`transformers-book_reviews.ipynb`](transformers-book_reviews.ipynb) |

### **BBC News**

| **Topic**              | **Description**                                      | **File**                                               |
|------------------------|------------------------------------------------------|--------------------------------------------------------|
| BBC News Classification| Text classification with the BBC news dataset        | [`nlp-bbc_news.ipynb`](nlp-bbc_news.ipynb)             |

## 📊 Datasets

| **Dataset**                       | **Description**                                 | **File**                                               |
|------------------------------------|-------------------------------------------------|--------------------------------------------------------|
| BBC News                           | Dataset containing BBC news articles            | [`bbc_news.csv`](data/bbc_news.csv)                    |
| Book Reviews Sample               | Sample dataset of book reviews                  | [`book_reviews_sample.csv`](data/book_reviews_sample.csv) |
| TripAdvisor Hotel Reviews         | A dataset of hotel reviews from TripAdvisor      | [`tripadvisor_hotel_reviews.csv`](data/tripadvisor_hotel_reviews.csv) |
| News Articles                     | Dataset containing various news articles         | [`news_articles.csv`](data/news_articles.csv)          |

## 🚀 Getting Started

To get started with the project and explore the notebooks, follow these steps:

1. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Start a Jupyter notebook:

    ```bash
    jupyter notebook
    ```

3. Open and run the notebooks under the `preprocessing/`, `classification/`, `vectorization/`, `topic-modelling`, `sentiment` to explore various NLP tasks.
