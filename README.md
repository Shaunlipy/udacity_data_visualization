# udacity data visualization
In this final project, I am analyzing the Titanic Data. This dataset has 891 passengers with 12 attributes including (PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked).

After running in iPython (code.ipynb), I found there are 177 missing values for Age variable. 687 missing values for Cabin variable. 2 missing values for Embarked variable.

## Design
For this project, I will use dimple.js for data visualization. And I will exclude Cabin variable since there are too many missing values. 

And I would recode the NaN of Age variable to 0 to see run the data visualization.

My purpose is to explore the variables to investigate the correlation with outcome variable Survived. I would like to find out what variables can have most indication on the Survived variable.

Before plotting, my intuition is: Age should be a strong variable, since the younger (children) people should be more likely to get onboard the lifeboat (from the movie). Perhaps the elder people are also likely to be survived.

Gender should be a strong indicator as well, most likely women should have more survived.

I would also like to see if First class passengers are more likely to be survived than Third class passengers (Passenger class should also be correlated with Fare: first class fare should be higher than third class).

## Gender vs. Survival
The first chart I investigate is to compare the gender vs survival. The purpose is to compare if gender has any indication that affects people's survival

![First Chart](https://github.com/Shaunlipy/udacity_data_visualization/blob/master/pics/4.png)

It looks very obvious that there are way more women survived than women.

## Passenger class vs Survival
Next, I inspected that the passenger class vs the survival, looking to reveal if passenger class can be an indication to the survival rate. 

![second Chart](https://github.com/Shaunlipy/udacity_data_visualization/blob/master/pics/5.png)

As shown from the picture, very obvious, the 1st class passengers have a large propotion survived.

## Age and Fare vs Survival
Now I plot age variable and fare variable vs Survival.

![third Chart](https://github.com/Shaunlipy/udacity_data_visualization/blob/master/pics/3.png)

As can seen from the picture. the lower age group seems to have higher people survived, and higher fare group have higher people survived.

# Feedbacks

After I check with several people and got feedback from them.

### First

In order to compare if survival is really affected by Gender, I should also compare the death count in addition to survival count.

As to the suggestion, I included the death count 

![fourth Chart](https://github.com/Shaunlipy/udacity_data_visualization/blob/master/pics/1.png)

Putting the death count next to the survival count can yield a much clearer comparison.

as well as the Passenger Class vs. the survival:

![fifth Chart](https://github.com/Shaunlipy/udacity_data_visualization/blob/master/pics/2.png)

### Second

In order to give a most intuitive image, I should directly plot the percentages of male survived (survived male over all male) vs. female survived (survived female over all female).

![Sixth Chart](https://github.com/Shaunlipy/udacity_data_visualization/blob/master/pics/6.png)

The passenger chart is also adapted to show the percentage of survival for each class

![Seventh Chart](https://github.com/Shaunlipy/udacity_data_visualization/blob/master/pics/7.png)

### Third

In order to give a better visualization of people's age vs. survival rate. I categorized age into different age groups: NA, 0-15, 15-30, 30-50, 50 and up. Then for each age group, I plot the number of people survived (yes) vs people dead (no).

![Eighth Chart](https://github.com/Shaunlipy/udacity_data_visualization/blob/master/pics/8.png)






