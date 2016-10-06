# udacity data visualization
In this final project, I am analyzing the Titanic Data. This dataset has 891 passengers with 12 attributes including (PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked).

After running in iPython (code.ipynb), I found there are 177 missing values for Age variable. 687 missing values for Cabin variable. 2 missing values for Embarked variable.

For this project, I will use dimple.js for data visualization. And I will exclude Cabin variable since there are too many missing values. 

And I would recode the NaN of Age variable to 999 mainly to see if those missing value have an indication on Survived outcome.

I then decide to explore the variables [Pclass, Sex, Age, SibSp, Parch, Fair, Embarked] to investigate the correlation with outcome variable Survived.

## Gender vs. Survival
The first chart I investigate is to compare 
