# nyc-taxi-data
This project contains an exploratory data analysis of New York city taxi data. It showed some important charts and insights on how some factors influence taxi fare, Also, it contains a couple of predictive models to predict fare amount based on some predictors.

***Steps to Follow in order to access the .ipynb file:***

1. Locate the src folder
2. In the src folder, you'll find 2 .ipynb files. Namely
    - nyc-taxi-exploratory-data-analysis.ipynb
    - nyc-taxi-predictive-model.ipynb

**EXPLORATORY DATA ANALYSIS**

The first file __(nyc-taxi-exploratory-data-analysis.ipynb)__ contains a series of exploratory data analysis about the new york city taxi data. Here, I was able to provide answers to some of the questions below:

1. What is the distribution of number of passengers per trip?
2. What is the distribution of payment_type?
3. What is the distribution of fare amount?
4. What is the distribution of tip amount?
5. What is the distribution of total amount?
6. What are top 5 busiest hours of the day?
7. What are the top 10 busiest locations of the city?
8. Which trip has the highest standard deviation of travel time?
9. Which trip has most consistent fares?  

**Some important plots can be seen below:**
  

*Passenger Count*

![Screenshot 2022-03-10 221514](https://user-images.githubusercontent.com/32384910/157651040-6c237b99-ff64-4775-83da-909ade31b2bb.png)

*Busiest Hours*

![Screenshot 2022-03-10 221824](https://user-images.githubusercontent.com/32384910/157651444-84b8159e-9d26-4a28-a77c-b3fcbaadfdee.png)

*Map of Busiest Locations*

![Screenshot 2022-03-10 221949](https://user-images.githubusercontent.com/32384910/157651682-6399ab07-ee3c-4bef-9000-ffa3599babfc.png)


**PREDICTIVE MODEL**

The second file __(nyc-taxi-predictive-model.ipynb)__ contains a predictive model for fare amount and tip amount. This consist of all the step by step stages before the models were built and how the best performing model was eventually selected. Some of the key steps are:

1. Preprocessing: Here, some of the columns were formatted correctly, merging the two different dataframes
2. Feature Engineering: Here, more preprocessing is done to prepare the dataset for the model stage. First, we check for null values and then do some feature engineering on the date/time to put it in a proper format for training. Also, a correlation plot is plotted to check what feature are correlated with the target variable before model building. 
3. Model Building: This was done using Scitlearn Pipeline in order to create pipes of regression models and finally select the best performing one
4. Model Evaluation: Model was evaluated for accuracy here

*Model pipeline result*

![Screenshot 2022-03-10 223127](https://user-images.githubusercontent.com/32384910/157653380-62698a87-86e4-4743-80fa-768c4b70794c.png)

*Model Evaluation Plot*

![Screenshot 2022-03-10 223220](https://user-images.githubusercontent.com/32384910/157653647-c638a982-9510-4301-a45c-7a4facdff821.png)







