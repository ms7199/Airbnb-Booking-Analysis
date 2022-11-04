# **Airbnb-Booking-Analysis**


It's an EDA(Exploratory Data Analysis) on Airbnb dataset(NYC 2019)

## Table of content

- [What is Airbnb?](#What-is-Airbnb?)
- [Problem Statement](#Problem-Statement)
- [Explore and analyze the data to discover key understandings (not limited to these) such as:](#Explore-and-analyze-the-data-to-discover-key-understandings-(not-limited-to-these)-such-as:)
- [Diving into dataset](#Diving-into-dataset)
- [Overall Observation/Conclusion:](#Overall-Observation/Conclusion:)

## **What is Airbnb?**

Airbnb, Inc. is an American company that operates an online marketplace for lodging, 
primarily homestays for vacation rentals, and tourism activities. 
Based in San Francisco, California, the platform is accessible via 
website and mobile app.    

Airbnb does not own any of the listed 
properties; instead, it profits by receiving commission from each 
booking. The company was founded in 2008 by Brian Chesky, Nathan 
Blecharczyk, and Joe Gebbia. Airbnb is a shortened version of its 
original name, AirBedandBreakfast.com.

The company has been criticized for enabling bait-and-switch scams, 
being involved in West Bank settlements, possibly driving up home 
rents and creating nuisances for those living near leased properties. 
The company is regulated by many jurisdictions, including the 
European Union and cities such as San Francisco and New York City.

## **Problem Statement**

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.

This dataset has around 49,000 observations in it with 16 columns and it is a mix between categorical and numeric values.
[click here to download Airbnb dataset](https://drive.google.com/file/d/1ioU5r9KEYSfwgfUi22SclVkx4l1a_8ou/view?usp=sharing)

## **Explore and analyze the data to discover key understandings (not limited to these) such as:** 
* What can we learn about different hosts and areas?
* What can we learn from predictions? (ex: locations, prices, reviews, etc)
* Which hosts are the busiest and why?
* Is there any noticeable difference of traffic among different areas and what could be the reason for it? 

## **Diving into dataset**
---
* There are 49,000 observations with various types of field in this dataset.

* Actually dataset has total 48895 fields and 16 columns in which 10 columns have numeric values and 6 columns have categorical values.

**List of field**:
---

| Column Name  | Description |
| ------------- | ------------- |
| id | ID of the listing  |
| name   |  Name of listing  |
| host_id  | ID of the host  |
| host_name  |  Name of the host |
| neighbourhood_group    | Neighbourhood group name |
| neighbourhood  | Neighbourhood area name   |
| latitude   | Latitude of the room   |
|longitude     | Longitude of the room  |
| room_type     | Type of room (Consist of 3 categories)  |
| price    |  Price In Dollars |
| minimum_nights    | Number of minimum nights allowed  |
|number_of_reviews     |  Number of reviews about a particular room  |
|  last_review   |  Date on which the last review was given  |
| reviews_per_month | Its a ratio(no. of reviews/30)   |
|  callculated_host_listings_count   | Amount of listing per host   |
| availability_365   | Number of days in a year when bookings are available   |



# **Overall Observation/Conclusion:**

* The majority of guests like individual rooms or complete homes over communal accommodations.

* Brooklyn and Manhattan are New York's two prestigious, wealthy, and upscale neighbourhoods.

* Some properties have minimum nightly stays that are greater than 365 days, which may appeal to students, low-wage workers, and immigrants.

* Even if a home's location greatly influences its price, just because a location is popular doesn't guarantee that the property will be occupied the majority of the time.

* Because the characteristics provided in this dataset are of such poor quality for determining the value of properties, performing a regression on it may have a significant error rate. By examining the correlation heatmap, we may observe this. We would require more features such as bedrooms, bathrooms, property age (we believed it would be a very essential one), the tax rate that applies to land, additional amenities in the room, and the distance to the closest hospital, store, or school. These characteristics and pricing may be closely related.

* With the help of time series analysis, it is feasible to create predictions about the occupancy rate at specific times of the month or season.

* It would be helpful if we got the average guest reviews of a property; this would help us understand the property better and may also affect the price. A little bit
