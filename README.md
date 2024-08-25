Hotel Bookings and Revenue Analysis Dashboard
This Power BI dashboard provides detailed insights into hotel bookings, revenue generation, and key performance indicators (KPIs) over a period from May to July. The data consists of bookings from multiple hotels, segmented by various dimensions like room type, city, booking platform, and more. This README describes the key components, calculations, and features of the dashboard.

Overview
The dashboard includes several KPIs, charts, and filters to help analyze hotel performance based on the following key metrics:

Revenue: Total revenue realized from successful bookings.
Total Bookings: The total number of bookings made.
Total Capacity: The total number of rooms available across all hotels.
Successful Bookings: The number of bookings that successfully resulted in check-ins.
Occupancy %: The percentage of successful bookings compared to the total room capacity.
Average Rating: The average customer ratings for the hotels.
Cancellation %: The percentage of canceled bookings out of the total bookings.
Realization %: The percentage of bookings that resulted in successful check-outs.
RevPAR: Revenue per available room, a key metric to evaluate hotel pricing and revenue efficiency.
ADR: Average Daily Rate, representing the average revenue generated per room sold.
No Show %: Percentage of bookings that resulted in a "No Show."
Booking % by Platform: Breakdown of bookings by various platforms like Makeyourtrip, Logtrip, Tripster, etc.
Booking % by Room Class: Distribution of bookings by room classes (Standard, Elite, Premium, Presidential).
Dashboard Components
Top Filters:

City Filter: Filter bookings and metrics by specific cities.
Room Class Filter: View bookings and KPIs by room categories like Standard, Elite, Premium, and Presidential.
Week No Filter: Filter by specific weeks within the data range.
Month Filter: Select data for specific months (May, June, July).
Key KPIs:

KPIs like Revenue, RevPAR, Occupancy %, ADR, and Realization % are displayed prominently at the top of the dashboard to give an instant view of performance.
Tables:

Property by Key Metrics: This table shows key metrics (e.g., RevPAR, Occupancy %, ADR, DSRN, Realization %) at a property level, allowing users to compare different hotels and their performance across cities.
Charts:

Column Stacked with Line Chart: This chart visualizes Realization % by booking platforms with ADR represented by a line, allowing users to compare platform performance.
Line Chart by Week: A trendline chart displaying week-over-week changes in ADR, RevPAR, and Occupancy %.
Table of Weekday vs Weekend Performance:

This table shows the performance of key metrics (e.g., RevPAR, Occupancy %, ADR, Realization %) split between weekdays and weekends.
Measures and Calculations
Revenue and Bookings:
Revenue: Sum of total revenue realized for all hotels.
Total Bookings: Count of all bookings across hotels.
Successful Bookings: Count of bookings that resulted in a successful check-out.
Occupancy %: (Total successful bookings / Total room capacity) * 100.
ADR (Average Daily Rate): Revenue / Total rooms sold.
Cancellation and No Show Metrics:
Cancellation %: (Total canceled bookings / Total bookings) * 100.
No Show %: (Total no-show bookings / Total bookings) * 100.
Realization and RevPAR:
Realization %: (Total checked out bookings / Total bookings) * 100.
RevPAR (Revenue Per Available Room): Total revenue / Total rooms available (whether occupied or not).
Daily Room Metrics:
DBRN (Daily Booked Room Nights): Average rooms booked per day.
DSRN (Daily Sellable Room Nights): Average rooms available for booking per day.
DURN (Daily Utilized Room Nights): Average rooms utilized by customers per day.
Week-over-Week (WoW) Changes:
Revenue WoW Change %: Percentage change in revenue from the previous week.
Occupancy WoW Change %: Percentage change in occupancy from the previous week.
ADR WoW Change %: Percentage change in ADR from the previous week.
RevPAR WoW Change %: Percentage change in RevPAR from the previous week.
Realization WoW Change %: Percentage change in realization from the previous week.
DSRN WoW Change %: Percentage change in DSRN from the previous week.
Conclusion
This Power BI dashboard enables stakeholders to evaluate hotel performance through various lenses—city, room class, booking platform, and more. The visualizations provide insights into revenue generation, occupancy rates, booking behavior, and customer satisfaction, helping hotel managers make data-driven decisions to optimize performance
