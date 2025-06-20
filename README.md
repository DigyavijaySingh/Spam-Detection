﻿# SMS Spam Detection

## Overview
The **SMS Spam Detection** model is a machine learning-based application that predicts whether an SMS message is **spam** or **not spam**. Built using Python and deployed on Streamlit, this tool helps users identify unwanted spam messages and improve mobile security.

## How the Model Works
The model processes the SMS text by:

1. **Preprocessing**: Text is cleaned by converting to lowercase, removing special characters, stopwords, and punctuation.
2. **Vectorization**: The cleaned text is transformed into a numerical format.
3. **Prediction**: A trained classifier predicts whether the message is spam or not.

## How It Helps People
Spam messages, often linked to phishing and unwanted ads, can be harmful. This app helps users by:

- Automatically detecting spam messages.
- Protecting users from potentially malicious content.
- Providing an easy-to-use interface to check messages for spam.

## Technology Used
- Python
- NLTK (Natural Language Toolkit)
- Scikit-learn
- Streamlit
- Pickle
