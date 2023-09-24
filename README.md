# Machine-Learning
Machine Learning on two different datasets - Predicting Adult Income and Car Insurance Claims

**Author**: Nian Vrey

### Business problem:

Analize and understand the data provided, then create a model to predict the outcome based on the data.

## Adult Income Dataset

### Goal
To analize the data and attempt to create as accurate of a model as possible.

### Data
The data provided describes some features of an adult. Below are some distributions of the features, more can be found in the notebook. The graphs are set up so that the one on the left simply shows the distribution, while the one on the right shows the distribution with regard to the Income

![Distribution of Age](https://github.com/YoungVoid/Machine-Learning/assets/51823073/b12f6426-a7be-4239-9c99-accf16e20ea7)

The Distribution of Age graph above shows that we have a good spread over the working class, with a few elderly datapoints as well. There are noticeable outliers, both in count and in Age.

![Distribution of Occupation](https://github.com/YoungVoid/Machine-Learning/assets/51823073/e6bd71ac-5cc4-4ca3-a8ec-4dc047e16dc8)

The Distribution of Occupation above shows that we again have a good spread of data. It is worth noting that there are a noticeable amount of missing records.

### The Model
The model chosen model, found in the notebook, would be the Base Random Forest Model. It is far from perfect however. As we can see on the accuracy stats below, it does not do well on the prediction of >50K. 

\<=50K Accuracy: 92%

\>50K Accuracy: 61%

Overall Accuracy: 85%

# Files
### Notebooks
Machine_Learning.ipynb - Main Google Colab Notebook for the project.

### Spreadsheets
adult.csv - Adult Income Dataset

Car_Insurance_Claim.csv - Car Insurance Claim Dataset

### Sources
[Adult Income Dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)

[Car Insurance Claim Dataset](https://www.kaggle.com/datasets/sagnik1511/car-insurance-data)
