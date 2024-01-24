# Text-Analysis-Project-The-Hunger-Games-Trilogy

## Project Overview

This project focuses on the textual analysis of two parts of "The Hunger Games" trilogy, namely "The Hunger Games" and "Catching Fire". The project aims to compare these two books in terms of various linguistic and thematic aspects.

### 1. Corpus Preparation:

#### 1.1 Data Loading and Description:
- The text of both "The Hunger Games" and "Catching Fire" was loaded to create a corpus for analysis.
- Dataset description: The dataset consists of the complete text of each book.

#### 1.2 Text Preprocessing:
- Normalization: Text data underwent normalization to ensure consistency.
- Tokenization: Sentences were tokenized into individual words.
- Stopword Removal: Common stopwords were removed to focus on meaningful content.
- Stemming: Words were stemmed to reduce them to their root forms.
- Word Frequency Count: The occurrences of each word were counted in the corpus.

### 2. Data Visualization:

#### 2.1 Bar Charts of Word Frequencies:
- Bar charts were created to visualize the frequency distribution of individual words in both books.

#### 2.2 Word Clouds:
- Word clouds were generated to visually represent common words shared between the two books and unique words specific to each.

### 3. Grouping and Topic Modeling:

#### 3.1 Document-Term Matrix:
- A document-term matrix was created to represent the frequency of terms in each chapter.
- Distance Metrics: Various distance metrics were calculated for clustering and dendrogram creation.
- Dendrogram: A dendrogram was created to visually group chapters based on their textual similarities.
- Topic Modeling (LDA): Latent Dirichlet Allocation (LDA) was employed to identify and analyze themes in the books.

### 4. Classification:

#### 4.1 Chapter Classification:
- Chapters were classified based on word occurrences using weighted binary, logarithmic, and weighted TF-IDF approaches.
- Confusion Matrix: A confusion matrix was generated to compare the performance of the three classifiers.

### 5. Sentiment Analysis:

#### 5.1 Sentiment Polarity Indicators:
- Sentiment polarity indicators were created to measure the sentiment of each book.
- Bar Charts and Sentiment Analysis: Visualizations were created to analyze the sentiment and mood polarity in both parts of the trilogy.

Feel free to explore the code, adapt it to other books or datasets, and enhance the analysis as needed. Happy exploring!
