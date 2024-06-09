# Subtheme_Sentiment_Analysis


This project performs sentiment analysis on text data, specifically focusing on predefined aspects and problems within customer reviews. The sentiment analysis aims to identify positive, negative, and neutral sentiments associated with different aspects and problems.

## Table of Contents

-- Overview

-- Setup Instructions

-- Methodology

-- Results


## Overview

This script preprocesses text data, identifies aspects and problems, and performs sentiment analysis using a lexicon-based approach. The analysis determines the sentiment of predefined aspects (e.g., "garage service", "wait time") and problems (e.g., "incorrect", "missing") within the reviews.

## Setup Instructions

### Prerequisites

Ensure you have Python installed on your system. The script uses several Python libraries, including pandas, numpy, and nltk.

### Installation

Clone the repository or download the script files.

Install the required Python libraries using pip:

pip install pandas numpy nltk

Download the necessary NLTK data:


-- import nltk

-- nltk.download('stopwords')

-- nltk.download('names')

-- nltk.download('punkt')

-- nltk.download('averaged_perceptron_tagger')

-- nltk.download('movie_reviews')


### Data

Ensure your dataset is in a CSV file format. Update the file path in the script to point to your dataset file.

Enter the row number to analyze when prompted.

The script will preprocess the text, identify aspects and problems, perform sentiment analysis, and display the results.

## Methodology

### 1.) Text Preprocessing:

-- Convert text to lowercase.

-- Remove non-alphabetic characters.

-- Tokenize the text into words.

### 2.) Aspect and Problem Identification:

-- Predefined lists of aspects and problems are used to identify relevant sentences or phrases in the text.

### 3.) Sentiment Analysis:

-- A lexicon-based approach is used to determine sentiment.

--Positive and negative word lists are derived from the NLTK movie reviews corpus.

--Sentiment scores for each aspect are calculated based on the presence of positive and negative words.

### 4.) Result Compilation:

-- Sentiment scores are aggregated, and a final sentiment (positive, negative, neutral) is determined for each aspect.
Results

The script prints the sentiment for each aspect and problem in the specified review. For example:

Subtheme Sentiments:

garage service positive

wait time negative

booking positive

value positive

money positive
