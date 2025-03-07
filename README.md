



</p>
<h1 align="center"> Nyc Taxi Trip Time Prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>


   ![UP4GA4s](https://user-images.githubusercontent.com/109129303/178731209-950c34d8-aff8-4d5f-9506-67c65a25a04f.jpg)



<p>Data and Problem Statement:

The data used in this study are all subsets of New York City Taxi, which contains observations on around 1.4 million+ of New York City taxi rides in the year 2016. To build the models, 1 million observations were used, of which 800,000+ were used for training and 200,000+ for validation. The main objective is to build a predictive model, which could help in predicting the duration time of the ride. This would in turn help them in matching the right cabs with the right customers quickly and efficiently.</p>

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 2 executable files, 1 text files , 1 directories as follows:</p>
<h4>Executable Files:</h4>
<ul>

 <li><b>NYCBaseline_Model.ipynb</b> - Includes all information on model performance of XGBoost on nyc taxi trip data with out proper feature engineering or exploratory data analysis </li>
  <li><b>Manoj_nyc_taxi_trip_time_prediction_.ipynb</b> - Includes the information of different model performance on nyc taxi trip historical data after proper feature engineering process</li>
</ul>

<h4>Output Files:</h4>
<ul>
  <li><b>result.txt</b> - Contains information about RMSE, MSE, R^2 of different models  .</li>
  
  </ul>



</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: XGboost </h2>

<p> XGBoost is a powerful approach for building supervised regression models. The validity of this statement can be inferred by knowing about its (XGBoost) objective function and base learners. The objective function contains loss function and a regularization term. It tells about the difference between actual values and predicted values, i.e how far the model results are from the real values. The most common loss functions in XGBoost for regression problems is reg:linear, and that for binary classification is reg:logistics. Ensemble learning involves training and combining individual models (known as base learners) to get a single prediction, and XGBoost is one of the ensemble learning methods. XGBoost expects to have the base learners which are uniformly bad at the remainder so that when all the predictions are combined, bad predictions cancels out and better one sums up to form final good predictions.



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
   
   
<h2> :book: Linear Regression </h2>

<p> Linear regression is one of the easiest and most popular Machine Learning algorithms. It is a statistical method that is used for predictive analysis. Linear regression makes predictions for continuous/real or numeric variables such as sales, salary, age, product price, etc.

Linear regression algorithm shows a linear relationship between a dependent (y) and one or more independent (y) variables, hence called as linear regression. Since linear regression shows the linear relationship, which means it finds how the value of the dependent variable is changing according to the value of the independent variable.
   
   y= a0+a1x+ ε

The linear regression model provides a sloped straight line representing the relationship between the variables. Consider the below image:
   
   

![linear-regression-in-machine-learning](https://user-images.githubusercontent.com/109129303/178734810-7d3c637c-a4ba-4b6e-9b4a-4444608da597.png)
   
<h2> :book: Ridge Regression </h2>

<p> The Ridge regression is a technique which is specialized to analyze multiple regression data which is multicollinearity in nature. Though linear regression and logistic regression are the most beloved members of the regression family, Ridge of L2 is a regularization model for linear regression
   
   For example, ridge regression can be used for the analysis of prostate-specific antigen and clinical measures among people who were about to have their prostates removed. The performance of ridge regression is good when there is a subset of true coefficients which are small or even zero. But it doesn’t give good results when all the true coefficients are moderately large. However, it can still perform linear regression over a narrow range of (small) λ values.
   
   
![rid](https://user-images.githubusercontent.com/109129303/178740313-b500f299-28a5-46ce-b4c6-6f50fdc9e380.jpg)
   
   
<h2> :book: Lasso Regression </h2>

<p> Lasso regression is a regularization technique. It is used over regression methods for a more accurate prediction. This model uses shrinkage. Shrinkage is where data values are shrunk towards a central point as the mean. The lasso procedure encourages simple, sparse models (i.e. models with fewer parameters). This particular type of regression is well-suited for models showing high levels of multicollinearity or when you want to automate certain parts of model selection, like variable selection/parameter elimination.

Lasso Regression uses L1 regularization technique . It is used when we have more features because it automatically performs feature selection.
   
   
   ![las](https://user-images.githubusercontent.com/109129303/178741355-539bfb09-a788-4c2a-98d0-701db9445986.jpg)
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

   
<h2> :clipboard: Execution Instruction</h2>   
<p>The order of execution of the program files is as follows:</p>


<p><b>1) Manoj_nyc_taxi_trip_time_prediction_.ipynb</b></p>
<p> This file must be executed, to define all the functions and variables required for regression operations in which different models executed. and to evaluate the model performance on unseen data


  
  ![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
   
     
<h2 id="credits"> :scroll: Credits</h2>

< Manoj Korukonda > | Avid Learner | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manoj-korukonda/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Manoj-Korukonda)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2> :books: References</h2>
<ul>
  <li><p>'NYC Taxi Trip Duration Prediction using Machine Learning'. [Online].</p>
      <p>Available: https://medium.com/@ShortHills_Tech/nyc-taxi-trip-duration-prediction-using-machine-learning-a92874bd761
  </li>
  
  <li><p>'XGBoost'. [Online].</p>
      <p>Available: https://medium.com/sfu-cspmp/xgboost-a-deep-dive-into-boosting-f06c9c41349</p>
  </li>
  <li><p>'Linear Regression '. [Online].</p>
      <p>Available:https://medium.com/analytics-vidhya/understanding-the-linear-regression-808c1f6941c0 /</p>
  </li>
  
  
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
</p>
  </li>
  
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
   
