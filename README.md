### Introduction:

The workshop series is designed with a focus on the practical aspects of machine learning. We will be working in Python and using real-world datasets from [Kaggle](https://www.kaggle.com), the machine learning platform most suited for the “learn by doing” philosophy. The series is targeted towards complete beginners familiar with Python, but it is also designed adaptively so that you will be challenged even if you have some familiarity with machine learning tools. 


The four-session workshop is going to be very hands-on and will focus on how to work with datasets. Instead of comprehensively covering every tool and concept, you will learn the minimal but most useful tools quickly and how to find other resources to explore further.  

Timeline:  
Session 1: 5:30-7:30 pm on Thursday March 28, 2019 at Aviation Room, HMC   
Session 2: 5:30-7:30 pm on Thursday April 4, 2019 at Shan 2454, HMC   
Session 3: 5:30-7:30 pm on Thursday April 11, 2019 at Aviation Room, HMC    
Session 4: 5:30-7:30 pm on Thursday April 18, 2019 at Shan 2454, HMC   

This series is a precursor to a future Deep Learning workshop series. 

### General structure of each two-hour session in the workshop series:
* Guided session
* Hands-on exercise
* Project work

Four sessions are planned in the series with the following time allocations:

| Sessions | Guided session (min) | Hands-on exercise (min) | Project work (min) | Total time (min) |
|----------|:----------:|:----------:|:----------:|:----------------:|
| 1 | 50 | 60 | 10 | 120 |
| 2 | 30 | 60 | 30 | 120 |
| 3 | 100 | -  | 20 | 120 |
| 4 | 70 | - | 50 | 120 |

### Independent projects:
Each participant would pick a dataset of their own choice and work on it in subsequent sessions of the workshop. Below is a list of example datasets one can choose from:

Simplest:  
* [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
* [House Prices: Predict sales prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

More involved:
* [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)
* [Bike Sharing Demand](https://www.kaggle.com/c/bike-sharing-demand/data)

Somewhat challenging:
* [New York City Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction)
* [New York City Taxi Trip Duration](https://www.kaggle.com/c/nyc-taxi-trip-duration/data)
* [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis/data)
* [Mercari Price Suggestion Challenge](https://www.kaggle.com/c/mercari-price-suggestion-challenge/data)


[Kaggle Competitions](https://www.kaggle.com/competitions) (past and current) as well as [Kaggle Datasets](https://www.kaggle.com/datasets) are an excellent resource to find datasets. Below are a few suggestions to note if you want to pick a dataset from outside the above list:
* Data must be in tabular format (csv files). We will cover other data formats in Deep Learning workshop series later on. Please don’t pick tabular data stored in Google BigQuery format as it is usually too  big to work with.
* Prefer past competitions that have a high participation, a lot of shared kernels and many topics in the discussion forum to learn from.
* Main features must not be textual unless you already know or plan to learn some natural language processing concepts within the time frame.
* Data size must be manageable with respect to the computation power you have access to, especially important to check for the recent competitions. You can also run notebooks in [Google Colab](https://research.google.com/colaboratory/faq.html) for free.
* It is better to pick a [competition dataset](https://www.kaggle.com/competitions) than one from the [dataset archive](https://www.kaggle.com/datasets) unless you have an idea about how to formulate the problem and choose evaluation metrics. Must check with a quick baseline model that the performance is not inappreciable for the formulated problem with respect to the decided metrics. 




### Topics covered in the guided sessions and hands-on exercises:  
Session 1: Exploratory Data Analysis and Feature Engineering using Pandas - 1
- Pandas dataframes as the data structure for datasets
- Converting csv files to dataframes 
- Slicing and indexing dataframes using conditionals as well as iloc and loc methods.
- Statistical summary and exploration of dataframes
- Detecting and filling missing values in the dataframes 
- Regular expressions for data extraction
- Feature engineering such as creating new features 
- Basic plots
- Correlation among features
- Basic operations such as dropping rows/columns, setting index, replacing values of a column using a dictionary, etc.

Session 2: Exploratory Data Analysis and Feature Engineering using Pandas - 2
- Split-apply-combine operations by grouping rows of a dataframe 
- Encoding categorical variables 
- Concatentating and merging dataframes 
- More operations such as sorting the rows, creating a dataframe from the scratch, etc. 

Session 3: Model Building, Tuning and Testing - 1
- Splitting dataset into training and testing sets
- Bias-variance tradeoff, overfitting and underfitting of models
- Training and validation of models for classification and regression
- Normalization and scaling of features
    
Session 4: Model Building, Tuning and Testing - 2
- Fine tuning hyperparameters
- Regularization
- Dimensionality reduction techniques such as Principal Component Analysis (PCA), Linear Discriminant Analysis (LDA), etc.
- Selecting evaluation metrics such as accuracy, precision, recall, F-1 score, ROC curve, etc.
- Bootstrapping models
- k-fold cross-validation

### Pre-requisites:
* Python programming basics (HMC CS-5 or equivalent should suffice)
* Some familiarity with common statistical concepts (HMC MATH-35 or equivalent should suffice)

It will be beyond the scope of the workshop series to cover the theory and mathematics behind the machine learning algorithms and participants are encouraged to learn them on their own and deepen their understanding. A gentle introduction will be covered in the workshop series and resource links will be given for self-study. The focus will be on the practical aspects of machine learning and the concepts like feature engineering, overfitting vs underfitting, cross-validation, etc. that are crucial for all varieties of machine learning algorithms, including deep neural networks that will be covered in a future Deep Learning series.

### Learning materials:
The learning material is shared on [Github](https://github.com/AashitaK/ML-Workshops) and is updated after every session. The material is designed to be self-sufficient and useful. You are also welcome to join our google group [HMC Machine Learning](https://groups.google.com/forum/#!forum/hmc-machine-learning) that we plan to use for the workshop as well as for the future activities.

### Team:
Instructor: Aashita Kesarwani  
TAs: Rex Asabor, Ben Langton and Qualan Woodard


Seats are limited, please register using [this link](https://forms.gle/wFA1q9eqG3hgn2xN6). It is important that you attend all four sessions of the series for it to be useful.
