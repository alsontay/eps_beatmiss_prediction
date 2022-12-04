## Guide to Running Group 14 Codes


Google Drive Link: https://drive.google.com/drive/folders/1P5MnUriy47xvm2hnELt6WACJGc8Hz9zs?usp=sharing
Throw the whole google drive and replace the data folder

To directly replicate report results without going through long run times, these are the recommended files to run:
1.4.1 EDA + Combining of Datasets for Alpha = 0.2
2.1.7 Stacking Classifier, with SMOTE and Alpha Dataset Variants
3.1.1 Backtesting Code

For Data Collection
1.0 Code to Select the top 100 Trending Stocks from Reddit
1.1.1 & 1.1.2 Code to Scrap Reddit
1.1.3 Code to Scrap Twitter
1.1.4 Code to get Earning Calls Transcript using API and get Sentiment Scores using finBERT
1.2 Code to get Sentiment Scores for Reddit and Twitter using VADER 

For Feature Engineering and EDA
1.3.1a-b Getting the aggregated Reddit and Twitter Scores for Alpha = 0.2 
1.3.2a-b Getting the aggregated Reddit and Twitter Scores for Alpha = 0.6 
1.3.3a-b Getting the aggregated Reddit and Twitter Scores for Alpha = 0.0
1.4.1 EDA + Combining of Datasets for Alpha = 0.2 (This is our main dataset that we use)
1.4.2 Combining of Datasets for Alpha = 0.6
1.4.3 Combining of Datasets for Alpha = 0.0

For Modelling and Evaluation
2.1.1 Logistic Regression + GridSearch
2.1.2 Random Forest + GridSearch
2.1.3 SVC + GridSearch
2.1.4 XGBoost + Bayes Optimization
2.1.5 LightGBM + Bayes Optimization
2.1.6 MLP Network
2.1.7 Stacking Classifier, with SMOTE and Alpha Dataset Variants

For Backtesting and Miscellaneous
3.1.1 Backtesting Data Preparation Code
3.1.2 Backtesting Code
4.1 Comparing Similarity for Reddit & Twitter Rankings
