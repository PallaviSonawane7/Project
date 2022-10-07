# Emotion Prediction On Twitter Data Using NLP

# Emotion Prediction On Twitter Data Using NLP
## Introduction
Technology today has become a momentous driving vehicle for communication worldwide.
Social media platforms like Twitter, Facebook, and Instagram are the most important arenas for expressing views on transformations happening in and around the world every day. 
Twitter is a rich origin of info for mining user opinions. 
This project reflects the idea of considering user opinions performing sentiment, emotion analysis and establishing conclusions on interesting topics using Machine Learning algorithms tuned-up using supervised learning to obtain outputs for sentiment emotion analysis respectively. 
Sentiment analysis desires to obtain sentiment polarity (positive or negative) and Emotion analysis intends to obtain emotion ( empty, sadness, anger, surprise, hate, love etc.,) from user data. 
Such analysis essentially serves as a gateway for consumer needs and generates growth opportunities in businesses.
It can help in analyzing the mistake and recovering the respective aspects and it is very helpful in new product launching or making any modification to current product to increase the sale.

## Challenges
- Lack of resources
- Comparative sentences
- Multiple aspects
- Sarcasm and irony sentences
- Web slang
- Unlabeled data
- Noisy text
- Lack content
- Negations
- Computation

## Solutions & Approaches
- Data Collection
- Data Cleaning
- Model Selection
    1. ML: (Support Vector Machines, Decision Tree, Logistic Regression, Multinomial Naïve Bayes)
    2. RNN: Neural Network where the output from the previous step is fed as input to the current step
    3. LSTM: LSTM stands for Long-Short Term Memory. LSTM is a type of recurrent neural network but is better than traditional recurrent neural networks in terms of    memory.
    4. BERT: BERT stands for Bidirectional Encoder Representations from Transformers and it is a state-of-the-art machine learning model used for NLP tasks

- Obtain  Accuracy
- Comparing the model accuracy

# Methodology and Techniques
## NLP Pipeline
- NLP pipeline is very important to building any kind of NLP problem.
- Text preprocessing step is the most important step in the NLP pipeline.
- We can use multiple techniques for feature extraction such as a bag of words, Tf-idf, n-grams, and word2vec, Count-Vectorizer.
- In model evaluation, we have to build multiple models and select the best model based on evaluation metrics.
- Deployment has three stages deployment, monitoring, and retraining.
![NLP Pipeline](https://github.com/PallaviSonawane7/Project/blob/main/Images/NLP%20Pipeline.png)

## Dataset Preparation
The dataset used is a Twitter dataset that was downloaded from various sources. The tweets include the user’s name, the text tweet and emoticons. Emoji’s are not included in the tweet. The dataset has 113300 tweets containing three columns. The first column contains the Tweet comments, the second contains the sentiment score and the third column contains the actual tweet. The emotion score takes 10 values. A score of 0:Anger,1:Criticism, 2:Fear, 3:Hate, 4:Joy, 5:Love, 6:Offensive, 7:Optimism, 8:Sadness, 9:Surprise, I gave emotions. The output is a floating-point number that lies in the range of zero to one which is then passed through the inverse transform to get the emotion class.
![Dataset](https://github.com/PallaviSonawane7/Project/blob/main/Images/Dataset.png)

## Dataset Visualisation
![Dataset Graph](https://github.com/PallaviSonawane7/Project/blob/main/Images/Data.jpg)

## Data Pre-processing
- Data cleaning- Such as Removal of punctuation, URLs, Tags 
- Tokenization, PoS-Tagging, Lemmatization
- Stop-word removal

## Project Flow
![Project Flow](https://github.com/PallaviSonawane7/Project/blob/main/Images/Project%20Flow.png)

## Results & Conclusion
Upon evaluating all the models we can conclude the following details i.e.

**Accuracy**
As far as the accuracy of the model is concerned BERT better than the LSTM model which in turn performs better than RNN and other ML models. BERT has shown the accuracy up to 76.00% which when compared to Bi-LSTM which has an accuracy of 71.00% is quiet higher in the field of Machine Learning.

**Classification Report**
BERT shows the best results for the emotion criticism with the precision score of 0.76, Bi-LSTM-0.71 and 0.68 for the ML model respectively.

![Comparing all Model Accuracy](https://github.com/PallaviSonawane7/Project/blob/main/Images/Result.png)


## 🚀 About Me
I have 7+ years of experience in Automation & Control Panel division, handling & delivering of projects.
I am hardworking, sincere, an enthusiastic professional.
I've always been passionate about learning latest technologies, Currently seeking a challenging job that would synergize my skills & experience with the objectives of the organization which provides constant & real time skills up gradation along with fulfillment of personal & professional goals.


## Authors
- [Pallavi Sonawane](https://github.com/PallaviSonawane7)
- Aditya Sharma


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/PallaviSonawane7/Project)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pallavi-sonawane7)


## 🛠 Skills
  - HMI/ SCADA & PLC Programming, Make: Siemens/Omron/Delta/Schneider Electric; Control Panels,Robotics
  - Programming Language: Python, Scikit-Learn, Tensorflow, Keras, NLTK, Numpy, Matplotlib, Sklearn, OpenCV,VbScript.
  - Data Analytics, Statistics, Machine Learning, Deep Neural N/w, Cloud Computing, NLP
  - Other Software Tool: Tableau, AWS Services, Autocad.
  - Flexibility and Adaptability
  - Ability to Work Under Pressure
  - Communication Skills
