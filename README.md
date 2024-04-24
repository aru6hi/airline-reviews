# airline-reviews-analysis

In recent decades, airline competition has received tremendous interest inside the research community, given the competition’s potentially extensive impacts on passengers, economies, and the society as a whole. Our analysis focuses on the reviews of the Top 10 rated airlines in 2023 sourced from Airline Quality (https://www.airlinequality.com) website.

Categories covered by our analysis include Passenger Reviews, Staff Service Quality, Seat Comfort, Inflight Entertainment, Food & Beverages and Value for Money.

Our Problem Statement is **Developing a tailored evaluation framework to identify the best airline based on reviews and factors including convenience, comfort, and service quality.**

List of Airlines

- Singapore Airlines
- Qatar Airways
- All Nippon Airways
- Emirates
- Japan Airlines
- Turkish Airlines
- Air France
- Cathay Pacific Airways
- EVA Air
- Korean Air

This dataset is provided under the MIT License.

## Contributors

- Verma Arushi (@aru6hi) - Gradient Boosting Regression, Data Preperation, SHAP analysis
- Mittal Palak (@PalakMittal27) - Sentiment analysis, Exploratory Data Analysis, Linear Regression

## Models Used
1. VADER
2. Linear Regression
3. Gradient Boosting Regression

## Conclusion
- Value for money and Sentiment have the highest feature importance in predicting Overall Ratings i.e. they have the highest impact on the Overall Ratings given by customers.
- Other factors: Seat Comfort, Staff Service, Food & Beverages, Inflight Entertainment have little to no impact on the final ratings of customers.
- Gradient Boosting Regression model performs better than Linear Regression model when there are more number of predictors.
- SHAP analysis can be used to interpret the predictions of machine learning models. It provides explanations for individual predictions by quantifying the contribution of each feature to the model's output.
- Thus, we can evaluate the performance of airlines based on customer reviews using the framework we found through Gradient Boosting Regression.

## Takeaways from the project
- Handling and cleaning datasets with large number of records
- Sentiment analysis of text using VADER
- Gradient Boosting Regression and Linear Regression from sklearn
- SHAP analysis

## References
https://www.kaggle.com/datasets/sujalsuthar/airlines-reviews

https://www.airlinequality.com

https://www.sciencedirect.com/science/article/pii/S2941198X24000125

https://github.com/AidanCooper/shap-analysis-guide

https://github.com/cjhutto/vaderSentiment
