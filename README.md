# ih_datamadpt1121_project_m3

<p align="left"><img src="https://cdn-images-1.medium.com/max/184/1*2GDcaeYIx_bQAZLxWM4PsQ@2x.png"></p>


In this Kaggle competition the aim is to predict the price of diamonds based on their characteristics. You should get the minimum RMSE to win the competition. 


<p align="center"><img src="https://media.giphy.com/media/fe6NAMLeTWZq3v9Nmg/giphy.gif"></p>

## **Data**

To start with the competition, you have a dataset with charcteristics from diamonds to train the model and another one to test it. This dataset is the one we used on final project module 2. 

## **Instructions**

First of all, you have to create an environment to install all the libraries. You can all it "env-proj3". The libraries you must install are:

    · Pyhton 3.7
    · Pandas
    · Sqlite 3
    · Sklearn 

You have to import the file diamonds_train.db, and make several queries and convert them into dataframes with Pandas. Then you merge all of them and create the final dataframe. We will train the model with this dataset, and then test it with diamonds_test.csv. Once you have imported the first dataset, you have to identify the features and the target.

Also, the categorical variables have to be converted into numbers with get_dummies function. And then join the numerical variables. 


After applying different algorithms to train the model and optimize it, the best one for this model is "RandomForestRegressor". Finally, we create the prediction and export it as a .csv called "Submission"

Also, you must import the diamonds_test.csv to test the train dataset. We split it with "test-train-split" to  test the dataset with X_train and y_train. 
With "RandomForestRegressor" we get the minimum RMSE, which was 558.


<p align="center"><img src="https://media.giphy.com/media/APqEbxBsVlkWSuFpth/giphy.gif"></p>


## **References**

- [Pandas](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html)

- [Sk-learn](https://scikit-learn.org/stable/)

- [SQLite](https://www.sqlite.org/index.html)