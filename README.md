# Twiiter-Sentiment-Analysis-Tool

Sentiment analysis, often referred to as opinion mining, is a subfield of natural language processing and data analysis that aims to determine the sentiment behind a series of words, used to gain an understanding of the attitudes, opinions, and emotions expressed within an online mention.

Below are the main types of sentiment analysis:

- Binary Sentiment Analysis  
The most straightforward and basic form of sentiment analysis. It involves categorizing opinions into binary outputs like positive or negative, or sometimes even neutral.

- Fine-Grained Sentiment Analysis  
This digs deeper than mere polarity detection by grading sentiments on a scale, such as ratings from one to five stars. It helps in distinguishing between levels of sentiment intensity by adding more outputs.

- Emotion Detection  
Emotion detection seeks to understand specific emotional states conveyed in the text, such as happiness, anger, sadness, or surprise.

- Intent Analysis  
The goal behind intent analysis is to understand the intent behind a text - whether a user intends to purchase, recommend, or complain about a product or service.

- Multilingual Sentiment Analysis  
It involves analyzing sentiments across different languages, which requires understanding cultural nuances and linguistic idiosyncrasies.

# Sentiment Analysis Models & Algorithms

Now that we have better understood the uses and types of sentiment analysis, let's get under the hood and understand some approaches on how we can carry out sentiment analysis. From a broad view, sentiment analysis is divided into the following categories based on their level of complexity:

- Rule-Based Systems
     Lexical Affinities  
     Valence Shifters  
     Conjunctions  
     Punctuation  

     
- Machine Learning Approaches  
At times, rule-based systems might not be as adaptable or scalable, and due to the intricate nature of language and its context-dependent meanings, these systems may not always grasp the subtleties in how language is used.
To overcome these limitations, machine learning techniques can be applied.

- Deep Learning Approaches  
Using deep learning is another level higher: these models have achieved state-of-the-art results in sentiment analysis by capturing complex patterns in data. These involves uses things such as Convolutionary Neural Networks (CNN), Transformers and BERT.

# Here are the step-by-step instructions performed:

- Run nltk.download('twitter_samples') to download the twitter_samples dataset  
- Split the data into both training and test sets, as well as training and test labelled data. Use the following parameters for your train_test_split function:  
     test_size=0.25  
     random_state=42  
- Instantiate a TF-IDF vectorizer with the following parameters:  
     ngram_range=(1, 3)  
     min_df=5  
     max_df=0.8  
- Fit and transform the training data  
- Transform the test data  
- Initialize the logistic regression classifier and train it  
- Use the trained classifier to predict the 5 given tweets and determine if they are positive or negative  


![image](https://github.com/RiyaMindhe/Twiiter-Sentiment-Analysis-Tool/assets/84629433/93271c9f-6824-4ea4-8382-1e836be9e676)




