# Context

Scraper and data for Funda.nl



This data was scraped from Funda.nl and contains house and apartment related data (e.g price and location).
See some of the column descriptions later below.

# You can find tabular data in the following path: data/data_clean.csv

Some column description
* 'address' : Street + house number
* 'postcode_city' : Postcode + City string
* 'postcode' : Only postoce
* 'city' : Location of the property on a city level
* 'ad_link' : Link which was used to scrape the data
* 'addownloaddate_time' : Date time of
* 'Asking price' : Current price of the propery
* 'Original asking price' : Original price of the property
* 'price' : cleaned asking price
* 'sqm_price': livingArea / price
* 'livingArea' : square meter size of the propery
* 'Plot size' : the plot size of the property
* 'htype' : apartment or house based on the 'adlink'
* 'Type apartment' : apartment type
* 'Number of stories' : how many stories a given property has

* ...

* 'Building type' :
* 'Year of construction' :
* 'Number of rooms' :
* 'Number of bath rooms' :

# A short EDA can be seen by opening the '03_eda.ipynb' notebook

You will see tables like this in it:


