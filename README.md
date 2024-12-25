# AtliQ Grands Hospitality Analysis


## Project Overview


Atliq Grands has seen a decline in its market share and revenue due to competitive pressures and management decisions. This project is centered around revitalizing the business by utilizing hospitality analytics to make well-informed decisions.


### Project Goal

This project aims to boost Atliq Grands' market share and revenue within the luxury business hotel sector. The company aims to surpass competitors and enhance management decision-making by applying data-driven strategies and business intelligence.

This project is a part of the Codebasics Bootcamp

**Here is my report link** - 
https://app.powerbi.com/view?r=eyJrIjoiNDUyMTU5NWQtZGRkNC00MzRjLThhMWItNDJkN2FjMzUwZGNkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9


## Data Structure and Data Modeling

I gathered the dataset used from Code Basics’ website.

The datasets contain Two types of tables -->

**Dimension table:** Static data like customer and product details.

**Fact table:** Transaction data.

* dim_date
* dim_hotels
* dim_rooms
* fact_aggregated_bookings
* fact_bookings

Here is the Datamodel that I have worked on and it's a STAR SCHEMA


![data model](https://github.com/Akashsingh1916/AtliQ-Grands-Hospitality--Analysis/assets/146354971/333260ba-ddb1-4ccc-8767-2ae75ce1524b)


## Power BI Dashboard Overview:

The dashboard comprises Four pages-->

### **1. Home Page** - This is a landing page, when a user log-in first time he or she will land on this page and they can navigate to different pages from the home page 


![home page final](https://github.com/Akashsingh1916/AtliQ-Grands-Hospitality--Analysis/assets/146354971/f44f6c30-5cb1-43a0-8d14-7e422fe8a1c5)


### 2. Overview Page - Here you will find an overview of all the metrics

![overview page final](https://github.com/Akashsingh1916/AtliQ-Grands-Hospitality--Analysis/assets/146354971/395e8f23-ca32-48c7-af53-ce66ee86d0a4)



### 3. Revenue & Occupancy Contributors Page (R&O) - This page tells you about the revenue and occupancy


![R 0 page final](https://github.com/Akashsingh1916/AtliQ-Grands-Hospitality--Analysis/assets/146354971/fd94276d-4fb9-4570-952a-e5ece4bc6e0f)



### 4. Booking & Average Rating Contributors Page (B& AR) - This page tells you about the Bookings and Ratings


![B   AR final page](https://github.com/Akashsingh1916/AtliQ-Grands-Hospitality--Analysis/assets/146354971/6b92173b-3099-4e37-80ff-d59d04e1a24e)


## Insights 

Here are Some Key Insights 

* Mumbai generated the highest revenue (661M) and Delhi generated the lowest revenue(290.92M)
* Luxury generated more revenue i.e. 61.62% as compared to the Business category which generated 38.82% of total revenue i.e. 1.69 billion.
* Occupancy percentage is highest for Delhi i.e.60.44 % inspite of having lowest DSRN i.e.435 and lowest for Bangalore i.e. 55.68 %.
* AtliQ Exotica is the best performer among all properties with 316M revenue, occupancy percentage is 57.20% and cancellation rate is 24.39 %.
* On Weekend (Fri and Sat) Occupancy percentage is 62.6 % which is more than weekdays 
* Mumbai is the top city in terms of booking followed by Hyderabad, Bangalore, and Delhi.
* Most of the Bookings are coming from other channels followed by Makeyourtrip, logtrip.
* Also Most of the Bookings occurred for the Elite room class(49K), followed by the standard room class (38K).


## Skills learnt from project

**key metrics:**

* RevPAR- Revenue per available room 
* ADR- Average Daily Rate 
* DBRN- Daily Booked Room Nights 
* DSRN- Daily sellable room nights 
* DURN- Daily Utilized Room 
* Realisation %
* occupancy and cancellation %

**Power BI fundamentals:**

* Data cleaning and Star schema modeling
* Learned about page navigation, tooltip, and conditional formatting.

**Soft skills:**

* Domain knowledge in hospitality
