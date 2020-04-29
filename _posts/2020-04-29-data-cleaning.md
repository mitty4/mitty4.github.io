---
published: false
---
## data cleaning

##### 4/28/2020
**https://www.kdnuggets.com/2019/11/data-cleaning-preprocessing-beginners.html

Funfacts for the day: most data scientist spend the majority of their day, up to 70%, on prepping data! 

###### Missing Values
When deciding what to do with missing values, consider dropping the whole row if more than 50% of the data is missing a value and you have enough data points to work with without the dropped ones. Another option, though less desireable in some cases, would be to fill in the missing value with a zero. Now, the most common, but not always the most appropriate method, is to use the SCiKitLearn python library method, imputerclass, to fill in the missing value with the mean, median or mode. And lastly from this article, one could fill in the value with the proceeding's value. 

###### Dummy Variables
Because machine learning only uses numerical data, the categorical data that is usually found in column names needs to be converted to dummy variables. A simple way to do so is to use One Hot Encoder from [sklearn.preprocessing](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
