# **Repository Introduction - Forex Prediction with Neural Networks and Sentiment Analysis**
Welcome to the repository for my Master's thesis in Applied Informatics! This project focuses on enhancing the accuracy of Forex (foreign exchange) prediction by leveraging various neural network and machine learning models, along with sentiment analysis techniques.

## **Objective**
The main goal of this thesis is to investigate and develop effective models for Forex prediction. By combining the power of neural networks, such as Stacked LSTM (Long Short-Term Memory) and FCNN (Fully Connected Neural Network), we aim to improve the accuracy of Forex price forecasts. Additionally, sentiment analysis techniques utilizing models such as FinBert, Vader, and Textblob are incorporated to extract sentiment information from daily tweets sourced from Twitter.

## **Contents**
This repository contains the implementation and evaluation of different models used in the thesis project. Here's an overview of the main components:
### **Neural Network Models:**
1. LSTM: Long Short-Term Memory networks have the ability to capture sequential patterns in time series data, making them suitable for Forex price prediction.
2. Stacked LSTM: A variant of LSTM that incorporates multiple LSTM layers to learn hierarchical representations and capture complex patterns.
3. Fully Connected Neural Network: A traditional neural network architecture with fully connected layers. 

### **Machine Learning Models:**
1. SVM: Support Vector Machines are popular supervised learning algorithms known for their effectiveness in classification tasks. We investigate the performance of SVM for Forex prediction. We explore its performance and compare it against LSTM and Stacked LSTM.

### **Sentiment Analysis Models:**
1. FinBert: A fine-tuned BERT (Bidirectional Encoder Representations from Transformers) model specifically trained for financial sentiment analysis.
2. Vader: A rule-based sentiment analysis model that uses lexical features and a pre-trained sentiment intensity lexicon.
3. Textblob: A simple and easy-to-use Python library for sentiment analysis.

### **Data Sources:**
1. Forex Price Data: Historical Forex price data is used as a key input for training and testing the prediction models.
2. Technical Indicators: A set of technical indicators (such as Moving Average, MACD, RSI, ADX, Bollinger Bands, etc) are calculated based on the Forex price data to provide additional features for the models.
3. Twitter Data: Daily tweets collected from Twitter by snscrape are utilized for sentiment analysis and extracting sentiment-related features.

## **Usage**
To use the code and replicate the experiments conducted in this thesis, follow the instructions provided in each model's respective directory. The necessary datasets, pre-processing steps, and model training procedures will be detailed within the documentation.

## **Results and Evaluation**
The thesis explores the performance of various models and evaluates their effectiveness in improving the accuracy of Forex prediction. The results and comparative analysis are presented, showcasing the strengths and limitations of each model. Additionally, discussions on the impact of sentiment analysis on Forex prediction are included.

## **Acknowledgments**
I would like to express my gratitude to my thesis advisor, research colleagues, and everyone who supported me throughout this project. Their guidance and insights were invaluable in the development of this research work.

Please feel free to explore the repository, examine the code, and refer to the documentation for more detailed information. If you have any questions or feedback, don't hesitate to contact me.
