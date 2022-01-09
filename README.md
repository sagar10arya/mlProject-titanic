# Titanic Surviaval Prediction Using Machine Learning 


#Project Description:
    The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.The titanic disaster was occurred around 100 years ago on 15
April, 1912, killing about 1500 passengers and crew members. One of the reasons of this disaster was due to lack of lifeboats for the passengers and crew.
Although there was the luck of survival as the womens, childrens and upper class people were given more priority.
    With the use of machine learning methods and the dataset, we will attempt to derive the correlation between factorssuch as sex, age, passenger class, fare, etc. for the chances of survival of passengers.

    In this project, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.
   
  #Objective
    In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.
 
 #Implementation
    *Importing the libraries.
    *Importing the datasets.
    *Cleaning and analyzing the dataset.
    *Creating functions with many machine learning models.
    *Showing the confusion matrix accuracy for all the models on the test data.


#Tools :
    *Python
    *Numpy
    *Matplotlib
    *Seaborn
    *Scikit-Learn
    *Machine Learning Algorithms
    


  #Data Set Column Descriptions:

    pclass: Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
    survived: Survival (0 = No; 1 = Yes)
    name: Name
    sex: Sex
    age: Age
    sibsp: Number of siblings/spouses aboard
    parch: Number of parents/children aboard
    fare: Passenger fare (British pound)
    embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
    adult_male: A male 18 or older (0 = No, 1=Yes)
    deck: Deck of the ship
    who: man (18+), woman (18+), child (<18)
    alive: Yes, no
    embarked_town: Port of embarkation ( Cherbourg, Queenstown, Southampton)
    class: Passenger class (1st; 2nd; 3rd)
    alone: 1= alone, 0= not alone ( you have at least 1 sibling, spouse, parent or child on board)
    
    
  Age:
      Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
      
  sibsp:
      The dataset defines family relations in this way:
      Sibling= brother, sister, stepbrother, stepsister
      Spouse= husband, wife (mistresses and fiancés were ignored)
      
  parch:
      The dataset defines family relations in this way:
      Parent= mother, father
      Child= daughter, son, stepdaughter, stepson
      Some children traveled only with a nanny, therefore parch=0 for them.


Result and Conclusion:
    
    *Women, children and first class passengers as well as people with a small family had a better chance of survival.
      *0 : Didn’t survived
      *1 : Survived


