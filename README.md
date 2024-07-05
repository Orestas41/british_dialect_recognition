<h1 align='center'>British Dialect Recognition</h1>
<h3 align='center'>Orestas Dulinskas</h3>
<h4 align='center'>July 2024</h4>

<h5 align='center'>https://www.kaggle.com/code/orestasdulinskas/british-dialect-recognition</h5>

## Background

Language, particularly its variations and nuances, plays a crucial role in understanding and appreciating the cultural and social fabrics of regions. English, as spoken in the UK and Ireland, is characterized by a rich tapestry of dialects, each with its distinct phonetic, lexical, and syntactic features. These dialects not only reflect historical and geographical influences but also serve as markers of identity for individuals and communities. The advent of machine learning and data science has opened new avenues for exploring these linguistic variations systematically. This project aims to leverage these technologies to analyze and predict English dialects based on audio recordings, contributing to the broader field of sociolinguistics and dialectology.

## Objective

The primary objective of this project is to train a recurrent neural network (RNN) model capable of predicting the dialect of English spoken by a speaker based on audio recordings. By doing so, the project seeks to:
1. Identify key linguistic features that distinguish different English dialects in the UK and Ireland.
2. Develop a robust and accurate machine learning model that can generalize across various speakers and contexts.

## Data

The dataset used for this project comprises recordings from speakers across a broad spectrum of dialects from the UK and Ireland. Participants self-identified their dialect from the following categories:

- Irish English
- Midlands English
- Northern English
- Scottish English
- Southern English
- Welsh English

To ensure comprehensive coverage of each dialect's unique features, different elicitation scripts were crafted for each speaker. However, a set of common sentences was included in all scripts to allow for direct comparison across dialects. These scripts were meticulously designed to highlight specific linguistic features pertinent to each dialect, facilitating contrastive analysis. Additionally, pronunciation variants of place names and other lexical items were captured.

Each elicitation line in the dataset is associated with a LINE_ID, an identifier linking the line to its source. This allows for the retrieval of the same line across different speakers and dialects, enabling detailed comparative analysis. The sources for these lines include Wikipedia, The Rainbow Passage, and modified lines from virtual assistant tasks, curated to include target words for accent elicitation while preserving the original content.

By utilizing this diverse and carefully curated dataset, the project aims to uncover the intricate patterns and distinctive characteristics of English dialects, ultimately leading to a model that can accurately predict dialects based on spoken language.
