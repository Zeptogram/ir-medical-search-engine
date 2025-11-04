# ir-medical-search-engine
> Information Retrieval Project for University Bicocca - Milan

## Introduction
The goal of this project is to develop a search engine capable of retrieving relevant answers to
user queries expressed in natural language. The queries are natural health-related questions
harvested from the NutritionFacts.org website.
### The main approach
The project has been developed on Google Colab. This document is structured as follows:
- Analysis of the Data: The first part of the project is focused on importing the doc-
uments, queries and relevance judgements and analyzing their distributions, sizes and
particular signs.
- Experiments and Evaluation: The second part is focused on Retrieval Pipelines and
the evaluation of different experiments using TF-IDF and BM25. PorterStemmer and
SnowballStemmer have been used as Stemmers, while the indexing has been done on
text, title and both title and text of the documents.
- Improvements to the performance: The third part is focused on trying to improve
the results obtained in the second part, using the Query Expansion techniques provided
by PyTerrier Query Rewriting and Expansion. Besides PyTerrier’s functions, the SpaCy
library has been tested, which uses Word Embeddings for expanding the Queries.
   Conclusions & Future Work: The last part is focused on collecting all the results and
giving final considerations and future work about the project.

## Authors 
- Elio Gargiulo 
- Cristian Piacente
