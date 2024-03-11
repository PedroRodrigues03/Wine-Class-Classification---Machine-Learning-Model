# Wine-Class-Classification---Machine-Learning-Model
This notebook looks into use Python-based Machine Learning and Data Science libraries in an attempt to build a Machine Learning model capable of predicting a wine class based on the given attributes.

I'm going to take the following steps:

* Problem Definition
* Data
* Evaluation
* Features
* Modelling

## 1. Problem Definition

In a statement
> Given a wine multiclass classification parameters about some wines, can i predict the right class for a new wine?

## 2. Data

The original dataset came from UCI Machine Learning Repository - https://archive.ics.uci.edu/dataset/109/wine

There is also a version of it available on Kaggle - https://www.kaggle.com/competitions/wine-m

## 3. Evaluation 
> If i reach 95% of accuracy at predicting the right class for an unknown wine during the proof of concept, i'll persue the project

## 4. Features

1. Attribute Information:
    * `Alcohol`
    * `Malic acid`
    * `Ash`
    * `Alcalinity of ash`
    * `Magnesium`
    * `Total phenols`
    * `Flavanoids`
    * `Nonflavanoid phenols`
    * `Proanthocyanins`
    * `Color intensity`
    * `Hue`
    * `OD280/OD315 of diluted wines`
    * `Proline`
    
2. target:
    * `class_0`
    * `class_1`
    * `class_2`

## 5. Modelling

For this kind of problem i followed across the sklearn model map - https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html

To perform the classification task i will:
* Use Decision Tree Classifiers
* Use RandomForestClassifier
* Use Support Vector Classification