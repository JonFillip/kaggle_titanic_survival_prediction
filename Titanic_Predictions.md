## Titanic Traveller Survivability Prediction

The aim of the mini project is predict whether or not a passenger survived based on attributes such as their age, sex, passenger class, where they embarked and more.

The data is sourced from the Kaggle [Titanic](https://www.kaggle.com/c/titanic) dataset. The data is split into two groups:

1. Training Set
2. Testing Set

#### Data Dictionary

| Variable    | Description | Key           |
| :---:       |    :----:   |    :---:      |
| survival    | Survival    | 0 = No, 1 = Yes   |
| pclass      | Ticket class| 1 = 1st, 2 = 2nd, 3 = 3rd      |
| sex         | sex         |               |
| Age         | Age in years|               |
| sibsp       | # of siblings / spouses aboard the Titanic|        |
| parch       | # of parents / children aboard the Titanic            |          |
| ticket      | Ticket number|              |
| fare        | Passenger fare |            |
| cabin       | Cabin number |              |
| embarked    | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton           |


#### Variable Notes

pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

#### Requirements 

- Pandas
- Scikit-Learn
- Matplotlib
- Numpy