# Spaceship_titanic_Kaggle_competition_logistic_regression

 

Project description:
Data set is about alternative titanic ship – spaceship travel to another planets but because it collided with dust cloud half of the passingers were transported to alternative dimension. Need help predict which passengers were transported to alternative dimenssion and help bring them back.

Choosing right model:
Because of data qualities (no linear data dependencies) was applied Logistic regression, KNeighborsClassifier and RandomForestClassifier.
Best parameters where chosen by GridSearch and manually changing them.

How to run API model:
<br> 1.To run API please install requirements file by using command:
pip install -r requirements.txt in Terminal
<br> 2. Run py application called app in main directory ProjectWorkSpaceshipTitanic

Data files:
Files can be find in Kaggle competitions site: https://www.kaggle.com/competitions/spaceship-titanic and this Git repository.




Analysis Results and assumptions:
By analysing data and looking for the best model it was find out that:
1.	Cumulated total spend amount in the spaceship was not so good variable compared to expenditure when knowing expenditure for different things and activities
2.	Because of high correlation in between TRAPPIST and 55 Canri e, 55 Canri destination was eliminated from the variables and that improved model prediction score. 
3.	Because of high correlation in between Earth and Mart departure planets, Mars was eliminated from the variables and that improved model prediction score
4.	To predict better results with variables destination 55 Canri and departure planet Mars – would be needed additional model.
