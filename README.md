# ChatGPT Sentiment Analysis on Twitter

💬 Sentiment analysis of ChatGPT on Twitter involving data scrapping and employing deep language models to identify, extract, and quantify the overall sentiment towards ChatGPT.

> Project Status: [Completed]

![download](https://user-images.githubusercontent.com/122936255/219124600-3665f753-04c9-465f-b3ff-5ab9c28db6f4.png)


## Project Overview
The goal of this project was to conduct a sentiment analysis using 5 different natural language processing (NLP) models to get insights into the overall sentiment towards ChatGPT on Twitter. A sentiment analysis identifies the emotions in the context of a tweet, extracting subjective information from the original data and classifying whether the underlying sentiment is positive, negative or neutral. Thus, providing a better understanding of the current social sentiment regarding the subject.

### Key Findings
Combining and comparing the models' different outputs, the overall sentiment regarding ChatGPT was found to be mostly neutral but slightly more skewed towards negative emotions in some cases. The opinions included in the tweets, on the other hand, were very skewed towards subjectivity as opposed to facts.

### Model outputs:

### Vader (Valence Aware Dictionary and sEntiment Reasoner):  
<img src="https://user-images.githubusercontent.com/122936255/220189070-110494be-6bf3-4cdc-b768-720411220317.png" width=50% height=50%>
<img src="https://user-images.githubusercontent.com/122936255/220189110-9977c06b-8568-4b96-9fc1-d00f30e63ba3.png" width=80% height=80%>

### RoBERTa (Robustly Optimized BERT Approach):  
<img src="https://user-images.githubusercontent.com/122936255/220189370-0aea4553-3c85-434b-9b23-b3606a02b67b.png" width=50% height=50%>

### Transformers Pipeline:  
<img src="https://user-images.githubusercontent.com/122936255/220189424-d0e93c76-2abd-48c2-aaf9-8f6d660ec77a.png" width=50% height=50%>

### TextBlob:  
<img src="https://user-images.githubusercontent.com/122936255/220189488-9ed38c01-89ea-4a48-a25f-2009ada4d1bd.png" width=50% height=50%>
<img src="https://user-images.githubusercontent.com/122936255/220189516-8038d22f-15f2-4507-beec-f6e2d704244c.png" width=80% height=80%>

### WordCloud:  
<img src="https://user-images.githubusercontent.com/122936255/220189551-aa31e7cf-e4f9-4e5c-872a-a2f00d3eddf4.png" width=80% height=80%>

### Links
* **Python Code:** [`chatgpt_sentiment_analysis.ipynb`](https://github.com/hafluz/sentiment_analysis/blob/main/Project_3_Twitter_Sentiment_Analysis.ipynb)  
* **Scrapped Tweets Dataset:** [`sentiment_dataset.csv`](https://github.com/hafluz/sentiment_analysis/blob/main/sentiment_dataset.csv)

### Methodology
* Scraping Tweets
* Perform Exploratory Data Analysis
* Perform data cleaning
* Perform Tokenization of tweets
* Sentiment Analysis with 5 different NLP models
* Data Visualization
* Data Querying and extracting insights

### Tools
* Python
* Pandas
* Numpy
* Matplorlib
* Seaborn
* Snscrape (Scraper for social networking services)
* NLTK (Natural Language Toolkit)
* VADER (Valence Aware Dictionary and sEntiment Reasoner)
* RoBERTa (Robustly Optimized BERT Approach)
* Transformers Pipeline
* TextBlob
* WordCloud


## Contact
Feel free to contact me with any questions or if you are interested in colaborating on other data analysis projects!

**Henrique Augsten Luz**

* **[Github profile](https://github.com/hafluz)**
* **[LinkedIn](https://www.linkedin.com/in/henrique-augsten)**
