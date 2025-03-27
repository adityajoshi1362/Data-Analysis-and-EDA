# Data-Analysis-and-EDA

in this project i have used dataset from kaggle
initilly i have gone through the data and found out problems in my data
then i have converted all the categorical columns to numerical columns using onehotencoder and label encoder
then i applied standard scaler to take all the data in a particular 

now as my data was ready
i applied logestic regression first
from logestic regression i was getting an accuracy of 0.2 percent
then i applied polynoial logestic regression 
from polynominal of degree 3 i was getting an accuracy of 0.91%

then i applied decision tree from that i wa getting an accuracy of 0.88

further i applied random forest and applied grid search cv to find out the best parameters 
from that i got an accuracy of 0.98%

further more i applied xgboost and used grid search cv 
i got an cross val score of 0.99% on scoring parameter of accuracy

so this xgboost model was my final model
