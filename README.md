# HASOC_2021
## Tackling Hate Speech and Offensive Content on Social Media

The internet has become a breeding ground for hate speech and other offensive content, posing a significant societal challenge. This type of language—whether offensive, harmful, disparaging, or obscene—undermines objective discourse and fuels radical arguments. As a result, many social media networks actively monitor user posts to mitigate the spread of such content.

### The Need for Automated Detection

Given the sheer volume of content posted online daily, there is a pressing need for automated methods to detect and classify questionable posts. This task aims to develop such methods, focusing specifically on the binary classification of conversational tweets.

### Classification Categories

The goal is to classify tweets into one of two categories:

- **(NOT) Non Hate-Offensive**: These tweets, comments, or replies do not contain any hate speech, profane, or offensive content.
- **(HOF) Hate and Offensive**: These tweets, comments, or replies contain hate speech, offensive, or profane content, or they support hate expressed in the parent tweet.

### Solution Overview

The solution presented is part of the HASOC_2021 Shared Task 1A, and it involves several key components, each encapsulated in an IPython notebook:

1. **dataset.ipynb**: 
   - This notebook handles data preprocessing. It cleans and prepares the dataset for analysis by removing noise and irrelevant information, ensuring the data is ready for subsequent modeling steps.

2. **Tf_idf_MachineLearning.ipynb**:
   - This notebook implements TF-IDF (Term Frequency-Inverse Document Frequency) combined with various machine learning algorithms. TF-IDF transforms the text data into numerical features based on the importance of words, which are then used by machine learning models to classify the tweets.

3. **gloveVectorML.ipynb**:
   - This notebook leverages GloVe (Global Vectors for Word Representation) embeddings combined with machine learning algorithms. GloVe provides a way to represent words in a continuous vector space where similar words have similar vectors, enhancing the model's ability to understand context and semantics.

4. **FineTuningTransformers.ipynb**:
   - This notebook focuses on fine-tuning pre-trained transformer models. Transformers, such as BERT or GPT, have revolutionized natural language processing by allowing for advanced contextual understanding and nuanced text classification.

By combining these approaches, the solution aims to create a robust system for automatically detecting and classifying hate speech and offensive content on social media platforms.
 
 
 ### ARCHITECTURE DIAGRAM
 ![example](https://github.com/basavraj-chinagundi/HASOC_2021/blob/main/architecture.jpg)
