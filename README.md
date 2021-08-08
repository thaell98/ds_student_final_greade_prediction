# Data Science Student final grade prediction: Project Overview
* Created a tool that predicts the grade of a given student
* Created and optimized reggresion and classification  model

## Code and Resources Used
**Python Version:** 3.7.6  

**Packages:** pandas, numpy, sklearn, matplotlib, seaborn

**Data source:** https://www.kaggle.com/larsen0966/student-performance-data-set

## Data Overview
Used data set contains following:

* School	
* Sex 
* Age	
* Address	
* Family size	
* Parent s cohabitation status	
* Mother/Father education	and job	
* Reason to choose this school	
* Guardian	
* Traveltime	
* Studytime	
* Failures
* School support	
* Family support
* Extra paid classes/activities	
* Attending Nursery school	
* Wanting to take higher education	
* Internet at home
* Romantic relationships
* Family realationship	
* Freetime
* Going out
* Alcohol consumption
* Health
* Absences	
* Final grade


## Model Building
First, I transformed the categorical values into dummy variables and split the data into train and test sets.


## Model Performance
The Ridge reggresion model far outperformed the other approaches.
* R2: 0.37256703525014867 
* MSE: 9.222150795494857 
* MAE: 2.129396817449551


