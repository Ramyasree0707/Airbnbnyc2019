# **Airbnb Bookings Exploratory Data Analysis (EDA)**

**Overview**


This repository contains the code and documentation for conducting an exploratory data analysis (EDA) on the Airbnb dataset. The dataset comprises approximately 49,000 observations and 16 columns, providing insights into various aspects of Airbnb listings, host activity, and customer reviews.

**Project Objective**


The primary objective of this project is to analyze the Airbnb dataset and extract actionable insights to inform strategic decisions and optimize platform performance. Key areas of analysis include factors influencing listing prices, neighborhood distribution, host impact on listing performance, and review patterns.

**Dataset Description**


**id:** Unique identifier for each listing

**name:** Name of the listing

**host_id:** Unique identifier for each host

**host_name:** Name of the host

**neighbourhood_group:** Location (grouped by neighborhood)

**neighbourhood:** Specific area within the neighborhood group

**latitude:** Latitude range of the listing

**longitude:** Longitude range of the listing

**room_type:** Type of listing (e.g., Entire home/apt, Private room, Shared room)

**price:** Price of the listing

**minimum_nights:** Minimum number of nights to be booked

**number_of_reviews:** Number of reviews for the listing

**last_review:** Date of the last review

**reviews_per_month:** Number of reviews per month

**calculated_host_listings_count:** Total number of listings managed by the host

**availability_365:** Availability of the listing throughout the year

**Technologies Used:**
Python

pandas

numpy

matplotlib

seaborn

**Key Insights**

Manhattan and Brooklyn are the most popular cities compared to the ramaining. Manhattan has most demand for Entire room/apt and Brooklyn has most demand for Private room type.

Enitire room/apt is most popular among room types, and it is also expensive compared to others.

Most of top listings are also in Manhattan.But, it has least number of reviews despite of being expensive and popular city

Staten Island has more number of reviews, and private rooms and Entire home/apt are mostly available. So, there can be more number of listings in Staten Islan.

As the host listing count increases price decreases.

Some hosts has multiple listings in same and different neighbourhood groups.

**Conclusion**

Through comprehensive data analysis and visualization, we gained valuable insights into various aspects of Airbnb listings and customer behavior. These insights can be leveraged to optimize business operations, enhance platform performance, and guide strategic decisions for Airbnb.


