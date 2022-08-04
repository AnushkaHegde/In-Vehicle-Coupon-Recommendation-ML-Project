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
- Git Familarity: go to the time 32:45, [git branching](https://www.youtube.com/watch?v=RGOj5yH7evk&t=1549s) to see collarative details. 
- Data Preprocessing 
- Explortory Data Analysis 
  - Coupon acception vs. reject Value modfication 
  - Extract insights on the relationship between features and target 
  - Feature selection/ Drop some features if we can 
  - Feature encoding/ Tranform sub-catergory for further algorithms
  
:triangular_flag_on_post: By July 24, 2022 
- Feature Engineering / Finish the remaining work from last week
  - Select features
    - Autoencoder feature selection 
  - Encode catergorical feature using various ways for further comparisons on same algorithm
    - One hot encoding
    - Ordinal encoding
    - Embedding encoding as a strengthness combination for the above two methods
    - Frequency & target enecoding 
    - CatBoost encoder 
<<<<<<< Updated upstream
  - Reference: [1](https://machinelearningmastery.com/how-to-prepare-categorical-data-for-deep-learning-in-python/), [2](https://medium.com/geekculture/feature-engineering-for-categorical-data-a77a04b3308), [3](https://dvboi.medium.com/coupon-usage-prediction-on-in-vehicle-recommendation-systems-a-ml-classification-case-study-ea37427c072f), [4](https://machinelearningmastery.com/autoencoder-for-classification/#:~:text=Autoencoder%20is%20a%20type%20of,and%20a%20decoder%20sub%2Dmodels), [5](https://neptune.ai/blog/how-to-compare-machine-learning-models-and-algorithms), [6](https://github.com/pythonprofilers/memory_profiler)
=======
  - Reference: [1](https://machinelearningmastery.com/how-to-prepare-categorical-data-for-deep-learning-in-python/), [2](https://medium.com/geekculture/feature-engineering-for-categorical-data-a77a04b3308), [3](https://dvboi.medium.com/coupon-usage-prediction-on-in-vehicle-recommendation-systems-a-ml-classification-case-study-ea37427c072f), [4](https://machinelearningmastery.com/autoencoder-for-classification/#:~:text=Autoencoder%20is%20a%20type%20of,and%20a%20decoder%20sub%2Dmodels)
>>>>>>> Stashed changes
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
    - To see if they correponds well/ algorithms work or not
    - Compare the features of these two potential clusters with the insights in EDA. 
Try potential models with performance metrics under different catergorical data coding styles from existing package.


:triangular_flag_on_post: By August 1, 2022
- Combine the encoding efforts with teamates, discuss how can do in a more reasonable way
- Split manunal coding task into 3 parts to corresponding people
- Keep in touch and help with problem solving during the time 
- Discuss the acheivement this stage and merge if work, otherwise, improve

:triangular_flag_on_post: By August 5, 2022
- Draft the report
- Tidy code in jupyter notebook for preparation of uploading to github
- Design slides for coming prensentation on August 10
- Details
  - Adjust the values for coupon acception or rejection in section 2.1  
  - Insights for section 2.3
  - Add autoencoder and catbooster part to section 3.2 
  - Logistic model implementation  -- Hemant
  - Hard & soft margin model implementation   -- Yan & Anushka
  - Naive bayes implementation    -- Anushka
  - Presentation graph for each part  -- We may discuss 
  - Write down the insights for each part and link word between sections   -- Yan draft first, then you can improve
  - Adjust the order number and correspoding hyperlinks for table of contents 
If you have further improvment ideas, just write down here. 

Improve all the time. 

# Frequently Asked Questions
0. What encoding style is the best?
1. Is it possible for we encode in different ways for the mixture of nomimal and ordinal categorical data? 
2. Do we need to do normalization or standardization?
3. Can the OridinalEncoder automatically detect the intrinsic order of the varible and assign corresponding values to it?

Based on the understanding of those questions, several trails can be done. 
