# Heavy_Equipment_Price_Prediction_Regression_Project

Prediction of the sale price of Bulldozers using machine learning tools.

The data and evaluation metric used is **(root mean square log error or RMSLE)** is from the Kaggle Bluebook for Bulldozers competition.

The techniques used in here have been inspired and adapted from the **fast.ai** machine learning course.

The problem is approached with the following machine learning modelling framework:-
6 Step Machine Learning Modelling Framework 
To work through these topics, the tools used are **Pandas, Matplotlib and NumPy for data anaylsis, as well as, Scikit-Learn for machine learning and modelling tasks**

Tools which can be used for each step of the machine learning modelling process.
We'll work through each step and by the end of the notebook, we'll have a trained machine learning model which predicts the sale price of a bulldozer given different characteristics about it.

**1. Problem Definition**
How well can we predict the future sale price of a bulldozer, given its characteristics previous examples of how much similar bulldozers have been sold for?

**2. Data**
Looking at the dataset from Kaggle, you can you it's a time series problem. This means there's a time attribute to dataset.
In this case, it's historical sales data of bulldozers. Including things like, model type, size, sale date and more.

There are 3 datasets:
**Train.csv** - Historical bulldozer sales examples up to 2011 (close to 400,000 examples with 50+ different attributes, including SalePrice which is the target variable).
**Valid.csv**- Historical bulldozer sales examples from January 1 2012 to April 30 2012 (close to 12,000 examples with the same attributes as Train.csv).
**Test.csv**- Historical bulldozer sales examples from May 1 2012 to November 2012 (close to 12,000 examples but missing the SalePrice attribute, as this is what we'll be trying to predict).

**3. Evaluation**
For this problem, Kaggle has set the evaluation metric to being root mean squared log error (RMSLE). As with many regression evaluations, the goal is to get this value as low as possible.

**4. Features**
For this dataset, Kaggle provide a data dictionary which contains information about what each attribute of the dataset means. You can download this file directly from the Kaggle competition page (account required) or view it on Google Sheets.
