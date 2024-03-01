# ******Sonar Rock VS Mine Prediction using Machine Learing****** 

***


## Problem Statement : 
In a war situation , two countries are fighting against each other in ocean. Both the countries have mounted Mines inside the ocean so as to prevent other country from invading into their territory by exloading mines as soon as they are above it. Sonar is a equipment which is used to find objects under water using sound waves. There will both rocks and mines be present inside the ocean and the Radar wants to distinquish between both of them. So constructing a machine learning model to predict whether the object detected by sonar is mine or rock.

***


![Sonar ML](https://github.com/KARTIKPARATKAR/Projects-Based-on-Machine-Learning/assets/100400207/a29bf00c-d94d-49c3-a92c-8f390e5a1427)

**In the above image**, a sonar equipment can be seen inside the oscean and mine is mounted at the bottom of sea with rock.

***

## **Work-Flow Of model:** ##

![workflow](https://github.com/KARTIKPARATKAR/Projects-Based-on-Machine-Learning/assets/100400207/b05aec03-db53-46ab-ab97-0763adf5f763)

## **Steps involved in work-flow are as follows:** ##

**1)Sonar-Data:**

In the laboratory setup, an experiment can be done where sonar is used to send the sound waves to the metal object and rock. Here metal is used because mine would be manufactured from metals only.Data is collected with both metal(mine) and rock. This data is used to train the machine learning model.

**2)Pre-Processing of Data-**

Data preprocessing state is very important to make data capable of fedding to the machine learning model. It involves a)Train_Test_Split b)Handling Missing Values c)Handling Categorical Feature d)Normalization of dataset etc.

**3)Logistic Regression Model-**

As this is a binary classification problem of whether the object detected is Rock or Mine,logistic regression is best to execute this issue. Logistic Regression is a statistical model that use mathematics to find relationship between two dataframes 

**4)Trained Logistic-Regression Model-**

After training the Logistic Regression model on Train data, We wll get Trained Logistic Regression Model.THis model has the capability of distinguishing the detected object by sonar is Rock or Mine. When we give new data, This trained model will give us output as the object detected is rock or mine.

***

**Dataset** Used for training and testing the logistic regression model is [here](https://github.com/KARTIKPARATKAR/Projects-Based-on-Machine-Learning/blob/main/Copy%20of%20sonar%20data.csv)

***

**Google Collab Workbook** is attached here [open](https://github.com/KARTIKPARATKAR/Projects-Based-on-Machine-Learning/blob/main/Sonar_RockVsMine_Prediction_Using_Logistic_Regression.ipynb)

***

## Model Evaluation
![model evaluation](https://github.com/KARTIKPARATKAR/Projects-Based-on-Machine-Learning/assets/100400207/00bdb694-6aaa-4fe7-9e8f-b55c169f1ade)

Here, You can observe that I have got a accuracy of 83% on training data and accuracy of 73% on testing data.

***

## Model predicting the detected object as Mine

![mine example output](https://github.com/KARTIKPARATKAR/Projects-Based-on-Machine-Learning/assets/100400207/69991814-ef1e-4977-bc79-086b64552000)

***

## model predicting the detected object as Rock












