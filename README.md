Real estate is not always about business or investments, but also one of the crucial 
issues for individuals. With the growing population and rise in housing shortages 
has managed to gaze the public interest in housing (A. Verma, 2022). The housing 
market is ever-changing, so it is important to provide accurate housing prices 
predictions. House prices are supposed to be correlated with economy. Despite the 
vast amount of data, reliable house price predictions are lacking (Fatbardha Maloku, 
2024).   
This project’s aims to examine and comprehend how various features might predict 
house prices using House Price Prediction Dataset. Using the python-based 
machine learning models, it analyzes how do diverse characteristics like: built year, 
grade, view, conditions, etc. affects the price of the houses. The model learns from 
the labeled data and calculate the price of house. The prediction obtained from this 
model might help buyers and sellers to decide in when is the best time to buy a 
home. 


I decided to work on 
https://www.kaggle.com/datasets/andykrause/kingcountysales?select=kingcounty
 sales.csv   
because of the following reasons: 
i. Comprehensive Feature Set 
ii. Data Volume 
iii. Data Relevance and Quality
iv. Potential for Exploratory Data Analysis (EDA)

**Algorithms used:**
i. Linear Regression
ii. Random Forest Regression
iii. Gradient Boosting Machine


**Results Obtained**

![image](https://github.com/user-attachments/assets/037fdf5b-585f-457a-9164-484b417c832b)

The linear regression algorithm did not perform as expected, with an R2 around 
64.7% reflecting low accuracy. This result might be because of the weak linear 
relationship between features and target variable, which is validated by the low 
correlation values (0.15-0.4) among few selected features during feature inspection.  
The Random Forest Regressor performed well in the dataset with an R2 of 91%. It 
might be because:

i. It handles non-linear relationships well and works well with high dimensional 
data. 


ii. It follows ensemble learning that improves the overall accuracy by 
combining multiple decision trees to produce strong learner. 


iii. Random forest performs well against outliers as it aggregates predictions 
from multiple trees.  


The hyperparameter tuning of Random Forest regressor did not work as expected, 
it might be because the model has not been trained and used all the required 
parameters.  


The Gradient Boosting Machine performed well in the dataset with an R2 of 90%. 
It might be because: 


i. It handles non-linear relationships well and works well with high dimensional 
data.

ii. It leverages the strengths of weak learners, as it is an ensemble model

iii. Hyperparameter tuning might have been done properly allowing the model 
to perform optimally. 

 
For the better performance of the model, further improvements can be made such as: 
1. Feature Engineering 
2. Hyperparameter Tuning 
3. Exploring with neural network architectures 
4. Experiments with LightBGM for comparative analysis

   
Beyond the scope of this project, it can be further expanded into real-time prediction 
system building a user-friendly interface for stakeholders. This could increase the 
practical utility of the system.

**Visualization of Prediction**

i. Linear Regression:

![image](https://github.com/user-attachments/assets/cbaa245b-a36b-423f-a617-7cd555e436c4)


ii. Random Forest Regression: 

![image](https://github.com/user-attachments/assets/ad5227c2-5762-4ad8-afde-6a3e3ba3bc23)


iii. Gradient Boosting Machine: 

![image](https://github.com/user-attachments/assets/de1ebf9f-3653-4d16-b4db-dd78984377bf)




