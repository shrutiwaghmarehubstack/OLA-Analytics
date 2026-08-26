# OLA RIDE BOOKINGS ANALYSIS

This project analyzes ride booking data from Ola for the month of July 2024, covering over 20,400 ride records. The goal is to uncover booking trends, cancellation patterns, revenue insights and customer/driver rating performance using Excel, SQL and Power BI.

📊 Dataset

The dataset includes the following key fields:
Booking Details: Date, Booking ID, Booking Status, Customer ID
Ride Details: Vehicle Type, Pickup/Drop Location, Ride Distance
Performance Metrics: V_TAT, C_TAT, Driver Ratings, Customer Ratings
Cancellations: Canceled by Customer/Driver (with reasons), Incomplete Rides
Payments: Booking Value, Payment Method

🎯 Objectives
Analyze booking success vs. cancellation trends
Identify top-performing vehicle types by ride volume and revenue
Understand cancellation reasons (customer-side vs. driver-side)
Evaluate driver and customer satisfaction through ratings
Build an interactive Power BI dashboard for stakeholder-level insights

🛠️ Tools & Technologies
Excel – Data cleaning, Power Query
SQL – Data extraction, aggregation and trend analysis
Power BI – Interactive dashboard for visualization

📈 Key Dashboard Views
Overall Summary – Total bookings, success rate, revenue overview
Vehicle Type Analysis – Ride volume and performance by vehicle category (Auto, Bike, eBike, Mini, Prime Sedan, Prime SUV, Prime Plus)
Revenue Analysis – Booking value trends by payment method (Cash, UPI, Credit/Debit Card)
Cancellations – Breakdown of cancellations by customer, driver and reason
Ratings – Driver and customer rating distribution

🔍 Key Insights
Out of ~20,400 total bookings, the overall ride success rate was 62%, with the remainder split across driver cancellations, customer cancellations and "Driver Not Found" cases.
Prime Sedan generated the highest total revenue among all vehicle types, followed closely by eBike and Auto, despite fairly even ride volumes across categories (~1,700–1,900 rides each).
Cash was the most used payment method, followed by UPI, while Credit and Debit Card usage remained minimal.
The leading cause of customer-side cancellations was "Driver is not moving towards pickup location," while the top driver-side cancellation reason was "Personal & Car related issue."
Average driver and customer ratings were nearly identical (~4.0 out of 5), indicating balanced satisfaction on both sides of completed rides.

SNAPSHOT
https://github.com/shrutiwaghmarehubstack/OLA-Analytics/blob/main/DASHBOARD/SNAPSHOT%20OF%20DASHBOARD.png
