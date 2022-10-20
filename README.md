# Store-Sales----Time-Series-Forecasting-Regression-project-

##OVERVIEW
Analyzing the success of a company's stores is one of the most crucial duties . Any store's key difficulty is anticipating sales and the inventory needed at each location in order to avoid both overstocking and understocking. This makes it possible for the company to offer the finest customer service while preventing losses, guaranteeing that the store can continue to operate.

This is a time series forecasting problem. In this project, I'll predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer.

Specifically, I'm to build a model that more accurately predicts the unit sales for thousands of items sold at different Favorita stores.

The training data includes dates, store, and product information, whether that item was being promoted, as well as the sales numbers. Additional files include supplementary information that may be useful in building your models

###File Descriptions and Data Field Information

train.csv

* The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.

* store_nbr identifies the store at which the products are sold.

* family identifies the type of product sold.

* sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).

* onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.

test.csv

* The test data, having the same features as the training data. You will predict the target sales for the dates in this file.

* The dates in the test data are for the 15 days after the last date in the training data.

transaction.csv

* Contains date, store_nbr and transaction made on that specific date.

sample_submission.csv

* A sample submission file in the correct format.

stores.csv

* Store metadata, including city, state, type, and cluster.
* cluster is a grouping of similar stores.

oil.csv

* Daily oil price which includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices.)

holidays_events.csv
* Holidays and Events, with metadata

####QUESTIONS
* Is the train dataset complete (has all the required dates)?
* Which dates have the lowest and highest sales for each year?
 * Which City is having most number of stores?
* Are certain stores selling more products?
* Did the earthquake strike on ecuador on April 16, 2016 had a negative impact on sales?

* Are sales affected by promotions?
* What family is with most sales?
* What family is with the least sales?
* Monthly sales trend/ over a period of time.
* What are the most sold items on Christmas?
* Sales of individual items over a period of time.

#####HYPOTHESIS

* Promotion positively impacts sales.
* Earthquake strike on ecuador on April 16, 2016 does not have impact on sales

