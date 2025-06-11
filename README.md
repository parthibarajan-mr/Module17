# Module17
Comparing Classifiers
Overall based on purely training the models with no hyperparameter tuning the Logistic Regression model makes the most sense to utilize as the accuracy is only a little lower but the training time required is much faster.

Business Understanding:
Data is from a Portuguese bank that used its own contact-center to do directed marketing campaigns.

Data Understanding:
The dataset collected is related to 17 campaigns that occurred between May 2008 and November 2010, corresponding to a total of 79354 contacts. During these phone campaigns, an attractive long-term deposit application, with good interest rates, was offered. For each contact, a large number of attributes was store and if there was a success (the target variable). For the whole database considered, there were 6499 successes (8% success rate).

Data Preparation:
This is the first step of Exploratory Data Analysis (EDA)

Dataset size is 41188 X 21.
There were no missing values.
y column: Rename to Deposit.

![image](https://github.com/user-attachments/assets/4a0145d1-e6da-4f0c-bc36-f5d079d100e3)


Note: Based on analysis and model metrcis, we learned that imbalanced dataset which is heavily weighted towards the unsuccessful marketing campaigns could not be used effectively to determine features which could provide best model performance.

Recommendations for the Future
Deeper Analysis of Underperforming Features: A more granular analysis could unravel why many features ended up having zero importance in the Decision Tree model and whether these features could be engineered differently to extract more predictive power.

Addressing Class Imbalance: Techniques to handle class imbalance could improve model sensitivity towards the minority class, which is critical in marketing strategies aimed at increasing customer conversion rates.

Extended Feature Engineering: More complex transformations and interactions between features could be explored to uncover hidden relationships that could improve model performance.

Longitudinal Analysis: Considering the dataset spans multiple years, a temporal analysis to understand how customer behavior and economic conditions change over time could enhance the model's robustness and relevance to current scenarios.
