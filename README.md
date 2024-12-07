## Reducing Customer Churn: Using Machine Learning to Predict Customer Retention at Syriatel Mobile Telecom

INTRODUCTION.

Business growth and development are one of the main motivators of organizational decision-making and policy-making. Every business leader wants to increase sales, clientele, and profitability, but they also have to do everything in their power to prevent losses.
In recent years, business experts and leaders have recognized customer satisfaction as a critical component in guaranteeing such growth and development. A business cannot record any cash inflows in terms of revenues, make any sales, or turn a profit if it does not have customers. This emphasizes how important it is for businesses to put policies in place that keep their current clientele.
Recent technological developments have also exacerbated business rivalry. When combined with increased market saturation, this competition means that it has become harder and more expensive for businesses in most sectors to aquire new clients, which means they must shift their focus to cementing relationships with existing customers.
Through this project, I am building a prediction model that identifies customer churning patterns, which can help develop mitigation strategies. The project is structured as follows:
1. Business Understanding.
2. Data Understanding.
3. Data preparation.
4. Exploratory Data Analysis.
5. Modelling.
6. Model Evaluation.
7. Recommendations and Conclusions.

## Business Understanding.  
Syriatel Mobile Telecom has emphasized the need to increase customer satisfaction and maintain its 8 million clientele in light of a growing combination of factors in the telecommunications markets, including competition, technological advancements, and globalization. The multinational telecom company from Syria restates its resolve to hold onto its market share by building "its reputation by focusing on customer satisfaction and social responsibility."
Even though these initiatives have been successful over the years, the business must be more dedicated to lowering customer attrition rates as they could jeopardize its position in the market, financial success, and expansion as a whole. The company can cut expenses, prevent losses, and boost sales by keeping its 8 million customers. 

Primary stakeholder:
- Syriatel Mobile Telecom

Other stakeholders:
- Shareholders
- Employees
- Customers

Research Objectives:
1. To determine the most suitable model to predict customer churn.
2. To establish a customer retention strategy to reduce churn.

Research questions:
1. Which machine learning model is the most suitable for predicting customer churn?
2. What strategies can Syriatel Mobile Telecom implement to retain customers and reduce churn rates?

## Data Understanding.  
The Churn in Telecom’s dataset from Kaggle contains information about customer activity and whether or not they cancelled their subscription with the Telecom firm. The goal of this dataset is to develop predictive models that can help the telecom business reduce the amount of money lost due to customers who don’t stick around for very long.
The dataset contains 3333 entries and 21 columns, including information about the state, account length, area code, phone number, international plan, voice mail plan, number of voice mail messages, total day minutes, total day calls, total day charge, total evening minutes, total evening calls, total evening charge, total night minutes, total night calls, total night charge, total international minutes, total international calls, total international charge, customer service calls and churn.

## Data preparation.

The analysis performed on the dataset included the following steps: 
- Data Cleaning: The dataset was checked per column to find missing values, duplicates, and outliers and dealt with them accordingly.
- Data Transformation: Categorical data in the churn column was converted into numerical data.
- Exploratory Data Analysis: Analysis was done on the data to check the distribution of features and the target and to identify possible correlations between features.
- Feature Engineering: Certain columns were transformed to enhance their usefulness. This included; Encoding categorical variables into numerical representations e.g area_code, international_plan, voice_mail_plan Normalization and Scaling features to a consistent range using the StandardScaler

By performing these steps, I aimed to gain a comprehensive understanding of the dataset and prepare it for further analysis and modelling.

## Modelling.
During the analysis, I developed and evaluated two classification models to gain insights and make predictions. 
## Model 1: Logistic regression model.
Baseline Model
The first logistic regression model was built by default parameters. The model accrued 86% training accuracy and 86% as well for test accuracy. The recall was 18%, precision 60% and 27% F1 score.

## Model 2: Decision Tree Classifier.
Baseline Model
The baseline model used the default parameters to train and test the model. The model has an accuracy of 92%, precision of 72%, recall of 75% and F1 score of 73%

## Visualizations.

Logistic Regression Confusion Matrix.

![image](https://github.com/Eugene-Asengi/Phase-3-Project/blob/ab956256e566f2a9cd8f040af6edcba1e1c4d926/Logistic%20regression%20confusion%20matrix.png)

Logistic Regression ROC curve

![image](https://github.com/Eugene-Asengi/Phase-3-Project/blob/968df52a78c88d44750d7b0d5f2ce6e17a3612f4/Logistic%20regression%20ROC%20curve.png)

Decision Tree Classifier.

![image]()
