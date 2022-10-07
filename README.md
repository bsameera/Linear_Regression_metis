# Metis_Linear_Regression

## Hostel World - Webscraping :



### Abstract:

The question behind my analysis is which features affect the ratings of the customers for each hostel.

My client is hostel world, which has hostels through out the major cities in different parts of the world. This facility rents hostels and the charges per night stay. 

The link to the website is - www.hostelworld.com

### Design : 

Hostelworld is a leading global Online Travel Agent (OTA) focused on the hostel market.

They have hostels all over the world in Europe, Asia, Africa, North America and South America.

They have over 20 years' experience, with more than 13 million reviews across more than 17,000 hostels in 179 countries.

Their website operates in 19 different languages and our mobile app in 13 languages.

There are private rooms which are pricier and shared rooms called dorms.

Mostly, the shared rooms are separate for each gender.

Some hostels have 

The data was taken from many cities all over the world. 



### Data Description:

The data was acquired using selenium and beautiful soup.

The target to be predicted is the overall rating of each hostel, by the customers.

The features are 19 in total.

All features are categorical, ( values with zeroes and ones ), except for one continuous variable starting_prices ( which is the rent per night in USD ).

The features are starting_prices, security, location, staff, atmosphere, cleanliness, value for money rating, free breakfast, free wifi, security lockers, laundry, 24 hour safety, etc. 

Total number of rows acquired - 1665

After data cleaning - 1082


### Algorithms : 

1. Statsmodel 

2. Ridge regression

2. LassoCV regression

The data was divided into three parts using train_test_split function.

    train data + validation data = 80 %  ( 60% + 20 % )

    test data = 20 %

### Tools:

1. Request and BeautifulSoup Python libraries to facilitate web scraping.

2. Pandas to clean, explore and generate the final data.

3. Statsmodels and SKLearn to implement various regression models.

4. Matplotlib and seaboard to visualize the data and present final results.

5. Python 3.8.5 to accomplish all the above tasks.


### Communication :

#### Final results are as follows -

R squared < 0.4

MAE - 0.39

RMSE - 0.5

Average predicted rating - 8.86

Average actual rating - 8.73

The predicted and actual ratings are almost same, which suggests the model’s performance is good.

