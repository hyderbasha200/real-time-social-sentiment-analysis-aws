# real-time-social-sentiment-analysis-aws

This repository contains code files for deploying the sentiment analysis model (RoBERTa) using Amazon SageMaker, as well as CSV files that present the results of two sentiment analysis processes conducted with Amazon SageMaker (RoBERTa) and Amazon Comprehend.

# Data

Kaggle dataset link: https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets?resource=download

# Architecture:

This architecture is designed for real-time monitoring and analysis of social sentiments using AWS, focusing on the Twitter dataset from the 2020 presidential elections. It integrates Amazon SageMaker, Amazon S3, Amazon Comprehend, and Amazon QuickSight to offer a comprehensive solution.

1. Twitter Dataset on Amazon S3: The dataset containing tweets from the 2020 presidential elections is stored in Amazon S3, a highly scalable and durable object storage service that acts as the primary repository for the raw Twitter data.

2. Amazon Comprehend for Sentiment Analysis: The textual content of the tweets is analyzed using Amazon Comprehend, a natural language processing service. Comprehend performs sentiment analysis by categorizing each tweet as positive, negative, or neutral and provides an overall sentiment score.

3. Amazon SageMaker for Customized Model Training and Deployment: Custom models are trained and deployed using Amazon SageMaker. This involves creating machine learning models that are specifically tailored to the Twitter dataset to enhance the accuracy of sentiment analysis. These trained models are then deployed on SageMaker for real-time tweet processing.

4. Amazon QuickSight for Real-time Visualization: Amazon QuickSight is used for the real-time visualization of sentiment trends. It generates interactive dashboards and reports, providing stakeholders, such as political analysts and campaign strategists, with current insights into the evolving sentiments on Twitter during the 2020 presidential elections.
