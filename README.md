# TimeSeries-Forecasting-Regression-Analysis
Regression Analysis Timeseries analysis corporation favorita dataset
In this project, we will predict item sales at corporation favorita in Ecuador. The train dataset includes dates, store and item information, whether that item was being promoted, and the unit sales.
train.csv
Includes the target unit_sales by date, store_nrb, and item_nrb and a unique id to label rows.

test.csv
Test data, with the date, store_nbr, item_nbr combinations that are to be predicted, along with the onpromotion information.
The test data has a small number of items that are not contained in the training data.

It also has supplementary information useful for machine learning modelling:
sample_submission.csv
This shows the correct format of submission format.
stores.csv
Includes city, state, type and cluster.

items.csv
Includes family, class and perishable.

transactions.csv
The count of sales transactions for each date, store_nrb combination. Only included for the training data timeframe.

oil.csv
Daily oil price. Includes values during both the train and test data timeframe.

holidays_events.csv
Holidays and Events, with metadata
A holiday that is transferred officially falls on that calendar day, but was moved to another date by the government. A transferred day is more like a normal day than a holiday. To find the day that it was actually celebrated, look for the corresponding row where type is Transfer. Days that are type Bridge are extra days added to a holiday (e.g., extending the break across a long weekend).
Additional holidays are days added a regular calendar holiday, for example, as typically happens around Christmas (making Christmas Eve a holiday).
