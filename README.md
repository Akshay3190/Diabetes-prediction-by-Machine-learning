# Diabetes-prediction-by-Machine-learning
<br>
Analyzed the data of 768 patients & predicted their diabetic status by using Support vector Machine model.
<br>
<br>
Work flow of the project will be as follows-
<br>
<br>
<img width="960" alt="work flow" src="https://github.com/Akshay3190/Diabetes-prediction-by-Machine-learning/assets/149465028/8d09d759-53b0-41d0-9272-d8ef2c4cba9e">
<br>
<br>
Libraries we used for the Processing the data-
<br>
<br>
1-Numpy
<br>
2-Pandas
<br>
3-Sikit learn
<br>
<br>
Categorized the data into 2 sectors like 'x' for the patient's entire health factors & 'y' for 'Outcome' that is as the diabetic status.
<br>
<br>
Standardisation of  the data-
<br>
We have data in numeric values & it has a wide range like blood pressure ranges from 60 to 120 & more. Similarly, we have data for ‘Pregnancies’,’ Glucose ’,’Sking thickness’ in various ranges & the difference is there then it will be difficult for our ML to predict the test data. To overcome it we need to standardize our data in the particular range  which will help our ML model to make better predictions.
<br>
We have to standardize data by using the function 'StandardScaler'.
<br>
<br>
Splitting data into train & test.
<br>
<br>
Trained model with the Support vector classifier function.
<br>
<br>
Running model-Support vector calssifier-
<br>
<br>
This is supervised learning model. In this, we have to provide data with 2 labels. 1st person is diabetic & another non diabetic. Once we train the model it will be trained support vector learning model & we will test the same by giving new data to it.
<br>
<br>
After checking the accuracy of both the training & test we checked the implementation of the model with new data.
<br>
<br>
Accuracy Score-
<br>
To check the accuracy of the model we used the 'accuracy score' function.
<br>
<br>
It’s a function that is a performance metric provided by sikit learn library  in Python. It is commonly used to evaluate the performance of a classification model by measuring the accuracy of its prediction.
<br>
<br>
Reshape new data-
<br>
While building the predictive system for new data we need to reshape the data that is we need to inform numpy array that we are going to predict the result for only one line of data.
