# Market-Entry-Analysis
## Description
This project focuses on predicting potential sales for ABG Motors, a Japanese car manufacturer, as they consider entering the Indian market. Using logistic regression on Japanese market data, a predictive model was developed to estimate purchase likelihood. The model was then applied to the Indian market to analyse the company's market entry.

## Train
The model was trained using logistic regression using multiple linear regression on Japanese market data, incorporating customer demographics and purchase behavior as key variables.
$Purchase(Prediction) = β₀ + β₁Curr_Age + β₂Gender + β₃Ann_ Income + β₄Age_car(segmented)$

## Key analysis
The predictive analysis for ABG Motors entering the Indian market yielded strong potential for success. Using a logistic regression model trained on Japanese market data, with variables like customer age, gender, income, and previous car age, the model was applied to Indian market data.
### Predicted Sales: 
The final result predicts 29,735 car sales in the first year, which significantly exceeds ABG Motors' target of 10,000 units.

### Significant Factors: 
Key drivers of the purchasing decision were annual income and age, with gender playing a secondary role. The normalization of income and segmentation of previous car age helped provide more relevant insights into potential customer behavior in the Indian market. The variables namely GENDER, ANN_INCOME(INR), AGE _CAR (segmented) are having a direct relationship with the purchase behaviour of the consumer amongst them AGE _CAR (segmented) has the highest direct relationship with purchase of 96% but on the other hand CURR_AGE is having an inverse relationship with purchase prediction that of -1%.

![image](https://github.com/user-attachments/assets/aab74562-58d5-434c-8503-e998863f1170)

These findings suggest a strong market alignment between the Japanese and Indian automotive sectors, and ABG Motors is well-positioned to exceed its initial sales target in the first year of market entry.
