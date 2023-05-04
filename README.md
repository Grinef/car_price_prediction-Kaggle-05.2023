The competition was held among all the Yandex Practicum students on my stream. This decision took the 7th place out of 50 participants.

In this competition, your task is to develop a model to predict the selling price of a car on the secondary market. (Regression)

features:
train.csv - information (~440,000) about car sales from auctions, which will be used as training data.
test.csv - information (~110,000) about car sales from auctions, which will be used as test data. Your task is to predict the 'sellingprice' value for each car in this dataset.
sample_submission.csv - predictions file in the correct format.
vin - identifier for each car in the test set.
sellingprice - Target feature. Predict the numerical value of the car's selling price for each car.
Description of data fields
'year' - year of production
'make' - manufacturer
'model' - model
'trim' - modification
'body' - body type
'transmission' - type of gearbox
'vin' - identifier (vin)
'state' - state of registration
'condition' - condition on a scale of 1-5
'odometer' - mileage in miles
'color' - body color
'interior' - interior color
'seller' - seller
'saledate' - date of sale

target:
'sellingprice' - selling price

target metric = MAPE.
