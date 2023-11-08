# Topic Modeling of Bank Customer Feedback Data

<img src="https://www.callcentrehelper.com/images/stories/2018/06/feedback-mindmap-760.jpg" style="float: left;" width="500" height="300" />

## Introduction
This project focuses on analyzing customer feedback data obtained from a bank to uncover hidden topics and gain insights into customer sentiments and concerns. The primary goal is to identify common themes within the feedback to help the bank make data-driven decisions for improving its services and customer satisfaction.

## EDA (Exploratory Data Analysis)
Exploratory Data Analysis (EDA) is a crucial step in understanding the dataset and preparing it for topic modeling. In this phase, the following tasks were performed:
- Data Cleaning: Preprocessing the customer feedback data by removing noise, such as special characters and stopwords.
- Tokenization: Breaking down the text into individual words or phrases.
- Data Visualization: Visualizing the dataset's statistics, word frequency, and word clouds to gain initial insights.

## LDA (Latent Dirichlet Allocation) Model
Latent Dirichlet Allocation (LDA) is a powerful technique used to discover underlying topics within text data. In this project, an LDA model was employed to extract topics from the bank customer feedback. The key steps in the LDA modeling process included:
- Creating a Document-Term Matrix: Transforming the preprocessed text data into a suitable format for LDA modeling.
- Training the LDA Model: Employing the Gensim library to train the LDA model with the customer feedback dataset.
- Identifying Topics: Analyzing the LDA model results to determine the most significant topics and their associated keywords.
- Visualizing Topics: Utilizing visualization tools, such as pyLDAvis, to provide an interactive representation of the topics.

## Summary
The project's findings and insights are summarized as follows:
- Identified Topics: A list of topics discovered within the bank customer feedback data, each associated with its top keywords.
-
By performing topic modeling and analysis of bank customer feedback data, the project aims to provide actionable insights to the bank, helping them enhance their services, address customer concerns, and ultimately improve customer satisfaction.
