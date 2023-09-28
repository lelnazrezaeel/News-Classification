# News-Classification

Welcome to the Politics News Classification NLP project! This project focuses on the classification of politics news articles using Natural Language Processing (NLP) techniques. The goal is to develop a model that can automatically predict the labels of news articles based on their content.

## <img width="25" height="25" src="https://img.icons8.com/dotty/80/41b883/overview-pages-2.png" alt="overview-pages-2"/> Overview

In this project, we leverage NLP techniques to analyze and classify politics news articles sourced from [Politifact](https://www.politifact.com/factchecks/list). Politifact provides a fact-checking service for politicians and public figures, categorizing statements into labels such as "true," "mostly true," "half true," "mostly false," "false," and "pants on fire." By crawling and processing the news articles from Politifact, we aim to build a robust model for predicting the veracity labels of politics-related statements.

## <img width="20" height="20" src="https://img.icons8.com/ios/50/41b883/database-options.png" alt="database-options"/> Dataset

We crawl the news articles and their associated labels from the [Politifact Fact Checks](https://www.politifact.com/factchecks/list) webpage. The dataset comprises a collection of politics news articles, each labeled with one of the following veracity levels:

- "True"
- "Mostly True"
- "Half True"
- "Mostly False"
- "False"
- "Pants on Fire"

The dataset is balanced and provides a diverse set of statements for training and evaluating our classification model.

## <img width="20" height="20" src="https://img.icons8.com/ios/50/41b883/parallel-tasks.png" alt="parallel-tasks"/> Structure

- ReadMe.md
- Phase1_Report.pdf
- Phase2_Report.pdf
- src/
  - (Project code files)
- data/
  - raw/
     - (Raw data files separated by labels, e.g., source1_true.csv, source2_false.csv)
  - clean/
     - (Cleaned data files, e.g., clean_data.csv)
  - wordbroken/
     - (Data separated by words, e.g., wordbroken_data.csv)
  - sentencebroken/
     - (Data separated by sentences, e.g., sentencebroken_data.csv)
- stats/
  - (Calculated information for the project data)
- latex source code
- models
  - language
  - tokenization
  - word2vec
- reports
  - word2vec
