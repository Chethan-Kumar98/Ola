# Ola
Ola Ride Hailing Services Data Analysis Project (July)
Project Overview:
This project involves analyzing ride hailing data from Ola for the month of July. The dataset contains comprehensive information on bookings, vehicle types, customer ratings, driver ratings, booking status, ride cancellations, and more. By using Power BI and MySQL, the data was cleaned, transformed, and analyzed to derive actionable insights regarding booking trends, revenue generation, customer and driver ratings, cancellations, and vehicle performance.

The analysis was carried out in two phases:
1. Power BI was used for data visualization and creating interactive dashboards.
2. MySQL was used for exploratory data analysis (EDA) to extract key insights and answer critical business questions.

Project Goal:
The goal of this project was to perform in-depth analysis on Ola ride hailing services data, uncover patterns, and provide valuable insights regarding bookings, cancellations, ride distances, vehicle performance, and revenue. By using both Power BI and MySQL, this project provides a comprehensive understanding of the ride hailing business, which can aid in decision-making and operational improvements.

Project Deliverables:
1. Interactive Dashboards:
   Main Dashboard
   Revenue Dashboard
   Vehicle Dashboard
   Bookings Dashboard
   Ratings Dashboard
2. Exploratory Data Analysis (EDA):
Insights derived from MySQL queries for a deeper understanding of the dataset.
Answers to key business questions related to booking status, cancellations, vehicle types, customer ratings, and more.

Key Features & Analysis:

Power BI Analysis:
1. Data Cleaning & Transformation:
   Power Query Editor was used to clean the data, handling Removal of duplicates, blanks, and null values,Correcting data types for proper analysis.

2. Created calculated columns and measures using DAX to calculate:
   Successful bookings.
   Unsuccessful bookings.
   Percentage of cancellations.

3. Visualizations in Power BI:
A series of interactive visuals were created to highlight key aspects of the ride hailing data, including:
Ride Volume Over Time: Displays booking trends over the month.
Booking Status Breakdown: Shows the distribution of successful and cancelled bookings.
Top 5 Vehicle Types by Ride Distance: Highlights the most popular vehicle types based on ride distance.
Average Customer Ratings by Vehicle Type: Visualizes customer ratings by vehicle type.
Cancelled Ride Reasons: Displays the reasons for ride cancellations.
Revenue by Payment Method: Breaks down revenue by payment methods used (e.g., UPI, cash, cards).
Bookings by Hour: Analyzes the booking patterns across different hours of the day.
Ride Distance Distribution Per Day: Shows the distribution of ride distances by day.
Driver Ratings Distribution: Displays the distribution of driver ratings.
Customer vs. Driver Ratings: Compares customer ratings with driver ratings.

4. Interactive Dashboards:

Created five interactive dashboards in Power BI to give a comprehensive view of the data:
Main Dashboard: A snapshot of key metrics and general information.
Revenue Dashboard: Focused on revenue trends and payment method analysis.
Vehicle Dashboard: Provided details about vehicle performance, ride distances, and bookings.
Bookings Dashboard: Analyzed booking status, cancellations, and booking trends.
Ratings Dashboard: Focused on customer and driver ratings, providing insights into service quality and satisfaction.

Exploratory Data Analysis with MySQL:

MySQL Queries:
Conducted exploratory data analysis by querying the dataset in MySQL to answer key business questions:
1. Retrieve all successful bookings: Extracted all bookings that were completed successfully.
2. Find the average ride distance for each vehicle type: Analyzed ride distance patterns across different vehicle types.
3. Get the total number of cancelled rides by customers: Counted the total number of rides cancelled by customers and their reasons.
4. List the top 5 customers who booked the highest number of rides: Identified high-value customers who booked the most rides.
5. Get the number of rides cancelled by drivers due to personal and car-related issues: Focused on cancellations caused by drivers.
6. Find the maximum and minimum driver ratings for Prime Sedan bookings: Analyzed driver ratings specifically for Prime Sedan bookings.
7. Retrieve all rides where payment was made using UPI: Filtered rides where UPI was used as the payment method.
8. Find the average customer rating per vehicle type: Analyzed customer ratings and their correlation with vehicle types.
9. Calculate the total booking value of rides completed successfully: Summed the total value of completed bookings.
10. List all incomplete rides along with the reason: Retrieved details about incomplete bookings along with reasons for failure.

Tools & Technologies Used:
Power BI: Used for data visualization, dashboard creation, and interactive analysis.
Power Query: Used for data cleaning and transformation before analysis.
DAX: Used for creating calculated columns and measures to generate key metrics (successful bookings, cancellations, etc.).
MySQL: Used for exploratory data analysis to answer specific business questions by querying the dataset.

