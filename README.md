# Table of contents
- [Summary](#summary)
- [Project Management](#tasks--deadlines)
- [Frequently Asked Questions](#frequently-asked-questions)

# Summary
This is a machine learning course project, In-vehicle coupon recommendation. The idea is to 1) predict if a customer will accept the coupon or not under learning algorithms from the scratch, 2) and find patterns between the predictors and the target variable. This can be as reference for companies to deliver coupons to potential customers so as to reduce the advertisement cost.

Initalized by the following people:
- Anushaka Hedge
- Krishna Hemant
- Yanming Liu

# Tasks & Deadlines 
:triangular_flag_on_post: By July 13, 2022
- Git Familarity: go to the time 32:45, [git branching](https://www.youtube.com/watch?v=RGOj5yH7evk&t=1549s) to see collarative details. &#10004;
- Data Preprocessing &#10004;
- Explortory Data Analysis &#10004;
  - Coupon acception vs. reject Value modfication :x:
  - Extract insights on the relationship between features and target :x:
  - Feature selection/ Drop some features if we can :x:
  - Feature encoding/ Tranform sub-catergory for further algorithms :x:
  
:triangular_flag_on_post: By July 24, 2022 
- Feature Engineering / Finish the remaining work from last week
  - Select features
    - Autoencoder feature selection 
  - Encode catergorical feature using various ways for further comparisons on same algorithm
    - One hot encoding
    - Ordinal encoding
    - Embedding encoding as a strengthness combination for the above two methods
    - Frequency & target enecoding 
  - Reference: [1](https://machinelearningmastery.com/how-to-prepare-categorical-data-for-deep-learning-in-python/), [2](https://medium.com/geekculture/feature-engineering-for-categorical-data-a77a04b3308), [3](https://dvboi.medium.com/coupon-usage-prediction-on-in-vehicle-recommendation-systems-a-ml-classification-case-study-ea37427c072f), [4](https://machinelearningmastery.com/autoencoder-for-classification/#:~:text=Autoencoder%20is%20a%20type%20of,and%20a%20decoder%20sub%2Dmodels)
- Try Models with sklearn package for a glimpse of classification
  - Logistic Regression
  - NN
  - Support Vector Machine
  - Deep Neural Network
  - Decision Tree, Random Forest
  - **[Collabrative Filtering](https://www.coursera.org/learn/unsupervised-learning-recommenders-reinforcement-learning?specialization=machine-learning-introduction)**
  - Clustering
- Determine performance metrics, comparison, and why 
  - Classification accuracy
  - F-score
  - ROC 
  - Original data vs. cluster data color-labeled by target for clustering
    - to see if they correponds well/ algorithms work or not
    - compare the features of these two potential clusters with the insights in EDA. 
Try potential models with performance metrics under different catergorical data coding styles from existing package.

# Frequently Asked Questions
0. What encoding style is the best?
1. Is it possible for we encode in different ways for the mixture of nomimal and ordinal categorical data? 
2. Do we need to do normalization or standardization?
3. Can the OridinalEncoder automatically detect the intrinsic order of the varible and assign corresponding values to it?

