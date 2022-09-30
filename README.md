# Payment Default Prediction
## Background

Bank Janata Taiwan in 2005 had a problem that has 22.12% default rate. That 22.12% default rate is too high than the fair value of the default rate that should be.This will made Bank Janata more lose revenue if it is not handled properly. We have goal to decrease the default rate to under 15% and increase potential revenue up to 5% by:

- Predict whether customers will default or not next month using predictive modelling
- Analyze the factor that affect the increase in default rate

## Business Metrics

Default Rate = Total Customer of Default / Total All Customer * 100%

## Exploratory Data Analysis

![Customer Overview](https://user-images.githubusercontent.com/114277079/193225412-5cfb0c5f-7db0-41a0-b6d3-a44928a80e01.JPG)
The following conclusions were reached based on the EDA procedure that was conducted:
1. Most credit card customer are women
2. Customers with university and high school educational backgrounds become customers with potential high to default
3. Customers with an age range under 25 years become customers with potential high to default
4. The last payment (September) has a high potential to determine the customer will default

## Data Pre-processing
1. Handling Duplicate Value and Missing Value
2. Feature Encoding
3. Data Transformation
4. Outlier Handling
5. Feature Selection
6. Imbalance Data Handling

## Modelling
1. Evaluation target is Precision (True Positive / (True Positive + False Positive))
2. 6 Model are tested and compared each model result to get best precision value
3. Random forest has the highest precision value compared to other models where the precision value obtained is 66%

## Business Insights & Recommendation

We create a business flow to make it easier to explain implement the model we created to achieve the goal. After implemented the model, we know who customer will potentially default next month and who non default. If model predict customer will default, we have recomendation that bank janata can do. We hope that the recommendations we provide can be achieved where the customer who is predicted to default will be no default.

### Before Implementation
![before treatment](https://user-images.githubusercontent.com/114277079/192738552-5cd717e7-5c06-4100-b822-20edda425b3b.png)

### After Implementation
![after treatment](https://user-images.githubusercontent.com/114277079/192738759-1de24fa2-9936-42e1-8b3a-4914b684cf64.png)

We suggest several steps banks can take to reduce their default ratio.
1. SMS & Phone Reminder
2. Payment Scheme with Installments
3. Credit restructuring
4. Collecting for Customers who do not make payments

We assume that if the recommendations we provide are implemented then we can potentialy decrease the default rate to 14% , potentialy increase Bank Revenue by 9%, and potentialy decrease loss by 33%

![Default Rate Final](https://user-images.githubusercontent.com/114277079/193225937-09ea35d9-396f-4bce-ad5b-cee4b0034843.JPG)

![Final Project - Floupin](https://user-images.githubusercontent.com/114277079/193232530-af239d05-1d95-46f2-aa07-9488e263793a.jpg)

![Final Project - Floupin (1)](https://user-images.githubusercontent.com/114277079/193232586-9c99b9f8-aafa-45bc-834e-5f1407948a19.jpg)

![Final Project - Floupin (2)](https://user-images.githubusercontent.com/114277079/193232616-f4cddb30-aac3-4ac1-a8ab-2b0f513dbb9d.jpg)
