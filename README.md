## Analysing New York City Airbnb Data.

New York City is the largest city in the United States, with a population of approximately 8.5 million people spread across five boroughs: Manhattan, Brooklyn, Queens, the Bronx, and Staten Island. It is a global hub for culture, finance, entertainment, and tourism, drawing millions of visitors each year.

Airbnb was founded in August 2008. As of 2023, Airbnb has hosted over 1.5 billion guests worldwide, with millions of listings in more than 220 countries and regions. It has grown into a major platform for short-term rentals and experiences, catering to both travelers and hosts across the globe.

In the context of Airbnb, New York City is one of the most popular and profitable markets globally. Due to the high demand for short-term rentals, especially in neighborhoods like Manhattan and Brooklyn, Airbnb has become a significant part of the city's tourism and accommodation landscape.

### Project:

In this project, we'll delve into a dataset featuring New York City properties listed on Airbnb. This dataset encompasses over 50,000 properties, with details on prices, locations, reviews, room types, and host information.

Our objective is to extract valuable insights from the data, including identifying the most prevalent room types and locations, and understanding how prices fluctuate based on room type and property location. Using machine learning models (Rinear Regression, Random Forest Regressor) we will perform price prediction modelling.

To achieve this, we will follow these steps:
1. Acquire and Explore the Data
2. Data Cleaning
3. Exploratory Data Analysis
4. Price prediction Modelling

### Understanding Data Variables

1. id - id number that identifies the property
2. name - Property name
3. host_id - id number that identifies the host
4. host_name - Host name
5. neighbourhood_group - The main regions of the city/Bprough
6. neighbourhood - The neighbourhoods
7. latitude - Property latitude
8. longitude - Property longitude
9. room_type - Type of the room
10. price - The price for one night
11. minimum_nights - Minimum amount of nights to book the place
12. number_of_reviews - Number of reviews received
13. last_review - Date of the last review
14. reviews_per_month - Amount of reviews per month
15. calculated_host_listings_count - Number of properties available on Airbnb owned by the host
16. availability_365 - Number of days of availability within 365 days
