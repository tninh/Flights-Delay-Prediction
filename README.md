# Flights-Delay-Prediction

## Instructions to run the webapp:

1. Enter in the webapp folder

2. run the command to install all the python librarires
   pip install -r requirements.txt

3. run the command python app.py

The app starts running on localhost:5000

## To evaluate a small dataset with logistic model: 

1. Download the dataset for the link that we put down in README file of data folder
2. Change the values at line `df2 = df1.loc[0:1500]` for any number of rows that you want. Small sets are recommended for avoiding memory error and saving time. 
3. Follow the steps in the notebook to select features and turn features into dense matrix. 
4. Train model and test for accuracy. 