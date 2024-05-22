# TweetSentimentAnalysis
NLP project to determine the emotions of tweets

## Project Architecture 

In this project, we use Naive Bayes, Logistic Regression, and BERT models to test our predictions. Also, we have tested two separate datasets to test our results. 

In the BERT model, we are feeding the BERT embeddings to CNN, followed by FNN layers. We also tested our results for roBERTa as well.


## How to run 

1. To run TweetSentimentAnalyis correctly, you should open the notebook in Google Colab. You can directly navigate to our original Colab directory here: https://colab.research.google.com/drive/15OwroDxWtz-aEBZ-Wld8m3sAaEgkj4wE?authuser=3#scrollTo=Au8Sx6tMkDRj .Alternatively, you can upload the notebook to your own Drive account and open Colab from there. The notebook is separated into multiple parts for readability since we have experimented with several models in several ways. You should access datasets to complete the preprocessing part correctly. You can see https://drive.google.com/file/d/175tkmdRAPL5GOzRf5zG0MAlClFc2qOic/view?usp=drive_link and https://drive.google.com/file/d/1xMtvAGAask2ZAewHPnoqSQ9Jn6CKZF_b/view?usp=drivesdk for our first and second dataset respectively. 

2. You should first import everything needed in the Imports section. Later, run the Preprocessing: Kaggle Dataset part to complete the preprocessing of the first dataset. Then, you can run Naive Bayes and Logistic Regression parts correctly. 

3. After completing these steps, you should run the method and class definitions under the BERT part. To find the results for the balanced dataset, run training with df1 parts. To see the results with the imbalanced dataset, run Training with reduced but still imbalanced parts.

4. For the second dataset, run Preprocess under Trying a different dataset: Semeval part. Later, you can see the results for Naive Bayes and Logistic regressions when you run those cells. Then, you can run the BERT parts, but please make sure that you have run every cell necessary for BERT in the first part.

5. To see the results for Binary Semeval results, run the cell named Trying Binary Semeval.

Please note that these processes take too much time and resources. We have used T4 GPU along with accelerated RAM, but we completed running this notebook for different Google accounts because of resource insufficiencies. You can see our report for all the final results. Most of our results are given under the cells.




