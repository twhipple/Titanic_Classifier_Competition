# Titanic_Classifier_Competition


![](https://raw.githubusercontent.com/twhipple/Wine_Classification/master/Images/wine-making-mirofoto.jpg)

*Predicting the quality of wine through classification. Source: 'mirofoto', freeimages.com*

## Intro
This is the basic model that I built for my first Kaggle Competition based on the data for the Titanic Machine Learning dataset.

From Kaggle:
"The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others."

![](https://raw.githubusercontent.com/twhipple/Wine_Classification/master/Images/Alcohol-quality.png)

*Alcohol seems to be related to the quality of wine.*


## README Outline
* Introduction 
* Project Summary
* Repo Contents
* Prerequisites
* Feature and Definitions
* Results
* Future Work
* Built With, Contributors, Authors, Acknowledgments


![](https://raw.githubusercontent.com/twhipple/Wine_Classification/master/Images/citric_acid_boxplot.png)

*Citric Acid boxplot demonstrating the correlation with Quality and showing a few outliers.*


## Repo Contents
This repo contains the following:
* README.md - this is where you are now!
* Notebook.ipynb - the Jupyter Notebook containing the finalized code for this project.
* LICENSE.md - the required license information.
* CONTRIBUTING.md 
* Images


## Libraries & Prerequisites
These are the libraries that I used in this project.
* import pandas as pd
* import numpy as np
* from sklearn.model_selection import train_test_split
* from sklearn.preprocessing import StandardScaler
* from sklearn.linear_model import LinearRegression
* from  sklearn.svm import SVR
* from sklearn.tree import DecisionTreeRegressor
* from sklearn.neighbors import KNeighborsRegressor
* from sklearn.metrics import mean_squared_error


## Features

* survival - Survival, 0 = No, 1 = Yes
* pclass - Ticket class, 1 = 1st, 2 = 2nd, 3 = 3rd
* sex - Sex
* Age - Age in years
* sibsp - # of siblings / spouses aboard the Titanic
* parch - # of parents / children aboard the Titanic
* ticket - Ticket number
* fare -Passenger fare
* cabin - Cabin number
* embarked - Port of Embarkation, C = Cherbourg, Q = Queenstown, S = Southampton


## Models
These are the models that I tried in this project:
* LogisticRegression
* Random Forest
* XGBoost
* K-Nearest Neighor (KNN)
* Support Vector Model (SVC)


![](https://raw.githubusercontent.com/twhipple/Wine_Classification/master/Images/Wine_heat_map.png)


## Conclusions
My Random Forest model had the best accuracy results. 


## Future Work
I could use Grid Search to modify the parameters and try improve the performance of my models. I also could use Cross Validation Score to assess the effectiveness of my model, particularly in order to avoid over-fitting.


![](https://raw.githubusercontent.com/twhipple/Wine_Classification/master/Images/bottles-of-wine-carlos-sillero.jpg)

*Which wine would you choose? Source: Carlos Sillero, freeimages.com*


## Built With:
Jupyter Notebook
Python 3.0
scikit.learn

## Contributing
Please read CONTRIBUTING.md for details

## Authors
Thomas Whipple

## License
Please read LICENSE.md for details

## Acknowledgments
Thank you to Kaggle Kernels for this competition and the dataset.
