# Quora-Insincere

## Problem Statement

An existential problem for any major website today is how to handle toxic and divisive content. Quora wants to tackle this problem head-on to keep their platform a place where users can feel safe sharing their knowledge with the world.

Quora is a platform that empowers people to learn from each other. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions -- those founded upon false premises, or that intend to make a statement rather than look for helpful answers

An insincere question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is insincere:

Has a non-neutral tone

  1) Has an exaggerated tone to underscore a point about a group of people
  2) Is rhetorical and meant to imply a statement about a group of people
  
Is disparaging or inflammatory

  1) Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype
  2) Makes disparaging attacks/insults against a specific person or group of people
  3) Based on an outlandish premise about a group of people
  4) Disparages against a characteristic that is not fixable and not measurable

Isn't grounded in reality

  1) Based on false information, or contains absurd assumptions
  2) Uses sexual content (incest, bestiality, pedophilia) for shock value, and not to seek genuine answers
  
 
 ## Dataset View and Analysis
 
 Kaggle Link of Dataset : https://www.kaggle.com/c/quora-insincere-questions-classification
 
  	qid	                             question_text	                      target
0	00002165364db923c7e6	 How did Quebec nationalists see their province...	 0


1) **Target Variable Distribution**

![image](https://user-images.githubusercontent.com/54737469/184329915-8fc5d0c2-33d9-4a01-b314-31988e14ae8a.png)

2) **Question Length Distrbution according to Target Variable**

![image](https://user-images.githubusercontent.com/54737469/184330063-1ec1c0f6-893c-4ff0-9453-7a7fcb9fb13f.png)

3) **Top Words Used in Dataset**

![image](https://user-images.githubusercontent.com/54737469/184330267-2ae2cee3-d387-477a-9909-ea3eed019bf9.png)

4) **Top Bigrams**

![image](https://user-images.githubusercontent.com/54737469/184330341-2d6c147a-aca4-4d55-998d-30b61e7a1bb3.png)

5) **Insincere questions Word Cloud**

![image](https://user-images.githubusercontent.com/54737469/184330462-5b33a191-b75b-4fcd-a80a-11d70b135e86.png)


## Results and Approach

==> Used LSTM and GRU based models for training 

==> Achieved **F1-Score of 64.2** with the help of GRU
==> Achieved **F1-Score of 63.7** with the help of LSTM
==> Currently learning more advanced model ans architecture , will come up with there results too (such as BERT , Transoformers)


You can see my complete approach in my notebook 
Also available here : https://www.kaggle.com/code/aryanml007/quora-insincere-eda-lstm-gru-embeddings



## Othe NLP Based Projects Link , please visit and provide your suggestions

Sentiment Analysis From Neespaper Headlines : https://www.kaggle.com/code/aryanml007/sentiment-analysis-using-news-headlines
Spam or Ham Message Classification Basic Approach : https://www.kaggle.com/code/aryanml007/spam-or-ham-sms-classifier-basic-approach
Spam or Ham Message Classification Deep Learning Approach : https://www.kaggle.com/code/aryanml007/spam-classifier-deep-learning-approach

