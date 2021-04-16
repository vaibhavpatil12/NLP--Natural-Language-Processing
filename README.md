# NLP--Natural-Language-Processing
NLP Assignments and Projects

Build Your Own News Search Engine

DESCRIPTION
Use text feature engineering (TF-IDF) and some rules to make our first search engine for news articles. For any input query, we’ll present the five most relevant news articles.

Problem Statement:

Reuters Ltd. is an international news agency headquartered in London and is a division of Thomson Reuters. The data was originally collected and labeled by Carnegie Group Inc. and Reuters Ltd. in the course of developing the construe text categorization system.

An important step before assessing similarity between documents, or between documents and a search query, is the right representation i.e., correct feature engineering. We’ll make a process that provides the most similar news articles to a given text string (search query).

Domain: News

Analysis to be done: Document similarity assessment to a search query using Tf-Idf

Content:

Dataset: ‘r8-all-terms.txt’

Dataset has no header. For each row, it has a label and the article text.

- Read the file in to a dataframe with Label and Text as columns.
- To perform feature engineering on text, build the list 'articles' out of the Text columns which holds the text. 
- Normalize the case
- Tokenize using word_tokenize
- Remove stop words
