# Income_Analysis

## Project Description

In this project we analyze a U.S. census data. The aim of this project is to estimate the income level in the data set and to test different models. 

- Created a model that accurately predicts whether an individual earns more than $ 50,000 
- Basic machine learning models have been tested and it has been observed which one gives the best results.

This project was written in python 3 and the following libraries were used: 

- Numpy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

## Data 

**Features**

- `age`: continuous.  
- `workclass`: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.  
- `fnlwgt`: final weight, continuous.  
- `education`: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.  
- `education-num`:  continuous.  
- `marital-status`: Represents the responding unit’s role in the family. Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.  
- `occupation`: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.  
- `relationship`: Represents the responding unit’s role in the family. Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.  
- `race`: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.  
- `sex`: Female, Male.  
- `capital-gain`: income from investment sources, apart from wages/salary, continuous.  
- `capital-loss`: losses from investment sources, apart from wages/salary, continuous.  
- `hours-per-week`: continuous.  
- `native-country`: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands. 

**Target**
- `income`: Income Class (<=50K, >50K) 
