# Wine Quality Prediction
A predictive system based on Machine Learning that measures the quality of the wine using exploratory data analysis and random forest algorithm of machine learning.
## Project Name:
Wine Quality Prediction
## Project Description:
In order to determine if a certain red wine is "good quality" or not, I built a classification model for this project using the Red Wine Quality dataset from the UCI ML Repository. In this dataset, each wine is assigned a "quality" value between 0 and 10. I changed the result to a binary output, meaning that each wine is either 'good quality', if it has score higher than 7 or it isn't, if its score is below than 7. 
11 input variables affect a wine's quality, they are as follows:

    1. Fixed acidity
    2. Volatile acidity
    3. Citric acid
    4. Residual sugar
    5. Chlorides
    6. Free sulfur dioxide
    7. Total sulfur dioxide
    8. Density
    9. pH
    10. Sulfates
    11. Alcohol
    
## Dataset:
I do not own the dataset, it was taken from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)

## Project Workflow:
- Importing required libraries and dataset
- Pre-processing the dataset and understanding it by performing EDA
- Feature Selection and preparing the data for modelling
- Training different models using train-data and test their accuracy on prediction of test-data
- Choosing the right model by comparing the results obtained frome each model

## Code 
The coding was done on [Google Colaboratory Notebook](https://colab.research.google.com/drive/1Ntfuh_LY9RqJynD-kruwvAqqhQjWnRh9?usp=sharing) as it provides pre-installed libraries for machine learning.

