# Home Loan Machine Learning and Tableau Project

# I. Business Problem

The business problem of home loan classification involves determining the creditworthiness of individuals or entities applying for home loans. This process is crucial for financial institutions, such as banks or mortgage lenders, to assess the risk associated with lending money for home purchases. Home loan classification aims to categorize loan applicants into different risk groups to make informed decisions about approving or denying loan applications

# II. Dataset

The dataset contains fundamental information about historical data of borrowing customers along with the approval status as target variable. This dataset is chosen because it comprises a diverse set of predictors, spanning across 13 variables through 614 observations, in multiple data types ranging from time data, categorical data to continuous and discrete data. This broad information would provide a solid foundation for further investigation and facilitate almost the knowledge covered in the course for classification problems.

# III Target variable: Loan_Status

It is a supervised learning about classification where we have to predict whether a loan would be approved or not.

# IV. OSEMN Pipeline

1. Obtain

2. Scrub

    2.1. Duplicated value

    2.2. Distribution

    2.3. Missing value

    2.4. outliers

3. Explore

    3.1. Exploratory Data Analysis (EDA)

      i) Univariate Analysis

      ii) Bivariate Analysis

    3.2. Encoding categorical variables

    3.3. Normalization

    3.4. Correlation

    3.5. SMOTE

    3.6. Feature Engineering

4. Model

    i) Logistic Regression

    ii) Random Forest

5. Intepret

# V. Conclusion

Logistic regression model returns accuracy of 81% while random forest model returns accuracy of 78%, therefore we conclude that logistic regression model is more effective than random forest model to predict loan status. The feature importance genereated by random forest indicates that the top five features affect loan approval or not are:

1. Credit history
2. Total income
3. Balance income (income which was duducted monthly installment)
4. EMI (equated monthly income)
5. Property located in semi-urban area

# VI. Visualization of Machine Learing Analysis

i) Univariate Analysis

![image](https://github.com/HazelDing/homeloan/assets/149340952/35295da3-bdd9-45ce-8230-aafcc536058f)

![image](https://github.com/HazelDing/homeloan/assets/149340952/9ed013cc-859c-44a0-aced-b3dcff8047ae)

![image](https://github.com/HazelDing/homeloan/assets/149340952/696fc813-f90b-441e-8a93-2b89f384a494)

ii) Bivariate Analysis

![image](https://github.com/HazelDing/homeloan/assets/149340952/c6b83639-75b2-4051-9218-f70cd5a430c8)

![image](https://github.com/HazelDing/homeloan/assets/149340952/f90a1ae1-eeb5-43c1-89cd-3145654813e9)

iii) Distribution of quatitative variables

![image](https://github.com/HazelDing/homeloan/assets/149340952/91b68299-fb99-4346-9d51-f7561cbb7f04)

![image](https://github.com/HazelDing/homeloan/assets/149340952/05717290-b25e-4418-a5ce-49c5c5a547d6)

iv) SMOTE smapling

![image](https://github.com/HazelDing/homeloan/assets/149340952/12cea666-a8f8-46e8-b05c-138caa98dde0)

v) Intepret

![image](https://github.com/HazelDing/homeloan/assets/149340952/8cea3c80-d7b8-4097-a0a1-7c271032c082)

![image](https://github.com/HazelDing/homeloan/assets/149340952/410008fe-4810-4158-86af-a262141bc2af)

VII Tableau dashboard of Home Loan Analysis

![Home Loan](https://github.com/HazelDing/homeloan/assets/149340952/377b9777-da25-45d1-a7cb-9201c478d2d7)









