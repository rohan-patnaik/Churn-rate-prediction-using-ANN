# Churn-rate-prediction-using-ANN
I tried to create an ANN model to predict the churn rate i.e. the rate of attrition for the customer data in our dataset.

Steps taken to complete this notebook :
>Separate dataset into test and train\
>Do one hot encodings for the dataset's categorical features\
>Standardize the data to feed to our model\
>Initialising the ANN\
>classifier = Sequential()\
>Compile and fit the model\
>Run it for a 100 epochs\
>Calculate the score at the end\
>Comes out to be close to 85% in our case\
>Optional step : Reiterate the process with changes to test and improve the overall score.


Shown below is a snapshot of the dataset : 

![image](https://user-images.githubusercontent.com/22250758/137970187-a1125bac-2545-4dd5-9ef9-95d5a71bcea2.png)

Shown below are the accuracies of the model :

![image](https://user-images.githubusercontent.com/22250758/137970218-e540fe94-db24-4fac-9600-23bd2e1028c1.png)

Shown below are the losses of the model :

![image](https://user-images.githubusercontent.com/22250758/137970472-d34cd673-b88f-4566-8fcc-bb0428525159.png)

