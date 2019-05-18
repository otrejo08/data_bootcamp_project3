# data_bootcamp_project3

https://otrejo08.github.io/data_bootcamp_project3/website/index.html

# Sydney and Melbourne-Airbnb-Analysis
Melbourne Sydney Airbnb Analysis for Rice Univiersity Sata Analystics Bootcamp

#Group Members:
- [Molly Eskelson](https://github.com/veyEskelson)
- [Kabrina Ramnath](https://github.com/kabrinaramnath)
- [Omar Trejo](https://github.com/otrejo08)
- [Raphael J Vasquez](https://github.com/Duktig511)


### Table of Contents

1. [Installation](#installation)
2. [Project Topic](#topic)
3. [Data](#data)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
The code in this project is written in Python 3.6.6 :: Anaconda custom (64-bit).
The following additional libraries have been used:
- wordcloud to generate wordclouds from the text of the reviews

- nltk for the Vader Sentiment Analyzer. The Vader lexicon has been downloaded nltk.downloader.download('vader_lexicon')

## Project Topic<a name="topic"></a>
In this project we analyze data from Airbnb listings for Sydney and Melbourne in 201# and 201#. 
The questions we are trying to answer in this project are the following:
-
-
- Can we find a way to classify negative and positive reviews based on text?

Topic modeling is a type of statistical modeling for discovering the abstract “topics” that occur in a collection of documents. Latent Dirichlet Allocation(LDA) is an example of topic model and is used to classify text in a document to a particular topic. It builds a topic per document model and words per topic model, modeled as Dirichlet distributions.
LDA (short for Latent Dirichlet Allocation) is an unsupervised machine-learning model that takes documents as input and finds topics as output. The model also says in what percentage each document talks about each topic.
A topic is represented as a weighted list of words.
LDA’s approach to topic modeling is it considers each document as a collection of topics in a certain proportion. And each topic as a collection of keywords, again, in a certain proportion.
Once you provide the algorithm with the number of topics, all it does it to rearrange the topics distribution within the documents and keywords distribution within the topics to obtain a good composition of topic-keywords distribution.



## Data <a name="data"></a>
The data has been made available by Airbnb inside, and the original source can be found [here](Add HTML)
# Text Cleaning or Preprocessing
-	Remove Punctuations, Numbers: Punctuations, Numbers doesn’t help much in processing the given text, if included, they will just increase the size of bag of words that we will create as last step and decrease the efficiency of algorithm.
-	Stemming: Take roots of the word
-	Convert each word into its lower case: For example, it useless to have same words in different cases (eg ‘good’ and ‘GOOD’).





## File Descriptions <a name="files"></a>
The Jupyter notebooks included in this project are:
- sentiment_analysis.ipynb, with the code to analyze the text reviews
- Review_ASCII_Negative.csv has Dataset has 6098 rows, 19 columns after cleaning it up.
- Review_ASCII_Positive.csv has Dataset has 161278 rows, 19 columns after cleaning it up.

## Results<a name="results"></a>
The following results are showed in the notebooks:
- 
-
-



## Licensing, Authors, Acknowledgements<a name="licensing"></a>
The Vader Sentiment Analyzer is due C.J. Hutto and Eric Gilbert fro the paper "VADER: A Parsimonious Rule-based Model for Sentiment 
Analysis of Social Media Text", available [here](http://comp.social.gatech.edu/papers/icwsm14.vader.hutto.pdf)




