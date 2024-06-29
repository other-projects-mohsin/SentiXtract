# Aspect_Based_Sentiment_Extraction
Created on: 26th Apr, 2023.

- This project focuses on a crucial area of Natural Language Processing called Aspect-Based Sentiment Analysis (ABSA), but simplifies the general ABSA problem.
- ABSA involves categorizing opinions by aspect and identifying the sentiment related to each aspect. Aspects are significant words for a business or organization, helping them understand customer sentiments.
-The general ABSA problem, a current research area in machine learning, involves finding all possible aspects and corresponding sentiments in a text. For example, in the sentence “I like apples very much, but I hate kiwi,” an ideal ABSA system identifies "apples" with a positive sentiment and "kiwi" with a negative sentiment.
- In this project, the aspect word/phrase is already given in the text, simplifying the task as we don't need to identify aspects. In the future, more general version of this problem, which includes identifying aspects as well (no aspects will be given in the dataset).

## A brief description of approach
- This work looks at using a *pre-trained language model*, *BERT* (Bidirectional Encoder Representation from Transformers), to solve the problem.
- BERT gives strong contextual embeddings which help solve many problems.
- The main idea is to explore BERT embeddings' modeling abilities using sentence pair input for aspect sentiment prediction.
- The model created reached 99.85% accuracy on training data and ~96% accuracy on test data.


**To install the dependencies:** <br>
```pip3 install -r requirements.txt```






