# Book recommender

Book recommender based on LLMs.

Dataset from https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata

Requires a .env file with an OpenAI key.

* data-exploration

Clean the data to have books_cleaned.csv

### vector-search

Performs similarity search 

### text-classification

Classification between fiction/nonfiction and run to have books_with_categories.csv

### sentiment-analysis

Performs sentiment analysis using DistilRoBERTa

### gradio-dashboard

Run to have a UI to perform similarity search (as in vector-search) using the whole dataset
