# Hotel Bookings and Revenue Analysis Dashboard

This Power BI dashboard provides comprehensive insights into hotel bookings, revenue generation, and key performance indicators (KPIs) for the period from May to July. It aggregates data from multiple hotels and segments it by dimensions such as room type, city, and booking platform. The following sections describe the dashboard's key components, calculations, and features.

## Overview

The dashboard offers detailed analysis of hotel performance with the following key metrics:

- **Revenue**: Total revenue realized from successful bookings.
- **Total Bookings**: The aggregate number of bookings made.
- **Total Capacity**: Total number of rooms available across all hotels.
- **Successful Bookings**: Number of bookings that resulted in check-ins.
- **Occupancy %**: Percentage of successful bookings relative to total room capacity.
- **Average Rating**: Average customer ratings for the hotels.
- **Cancellation %**: Percentage of bookings that were canceled.
- **Realization %**: Percentage of bookings that resulted in successful check-outs.
- **RevPAR**: Revenue per Available Room, reflecting pricing and revenue efficiency.
- **ADR**: Average Daily Rate, showing the average revenue per room sold.
- **No Show %**: Percentage of bookings that resulted in a "No Show."
- **Booking % by Platform**: Distribution of bookings by platforms like Makeyourtrip, Logtrip, Tripster, etc.
- **Booking % by Room Class**: Breakdown of bookings by room classes such as Standard, Elite, Premium, Presidential.

## Dashboard Components

### Top Filters

- **City Filter**: Allows users to filter bookings and metrics by specific cities.
- **Room Class Filter**: Enables analysis by room categories (Standard, Elite, Premium, Presidential).
- **Week No Filter**: Filters data by specific weeks within the range.
- **Month Filter**: Selects data for May, June, or July.

### Key KPIs

Prominently displayed KPIs provide an instant view of performance:

- Revenue
- RevPAR
- Occupancy %
- ADR
- Realization %

### Tables

- **Property by Key Metrics**: Displays key metrics (e.g., RevPAR, Occupancy %, ADR, DSRN, Realization %) at the property level for comparison across hotels and cities.

### Charts

- **Column Stacked with Line Chart**: Visualizes Realization % by booking platforms with ADR represented as a line, facilitating platform performance comparisons.
- **Line Chart by Week**: Displays week-over-week changes in ADR, RevPAR, and Occupancy %.

### Table of Weekday vs Weekend Performance

- Shows performance metrics (e.g., RevPAR, Occupancy %, ADR, Realization %) split between weekdays and weekends.

## Measures and Calculations

### Revenue and Bookings

- **Revenue**: Sum of total revenue for all hotels.
- **Total Bookings**: Count of all bookings.
- **Successful Bookings**: Count of bookings resulting in successful check-outs.
- **Occupancy %**: `(Total successful bookings / Total room capacity) * 100`
- **ADR (Average Daily Rate)**: `Revenue / Total rooms sold`

### Cancellation and No Show Metrics

- **Cancellation %**: `(Total canceled bookings / Total bookings) * 100`
- **No Show %**: `(Total no-show bookings / Total bookings) * 100`

### Realization and RevPAR

- **Realization %**: `(Total checked-out bookings / Total bookings) * 100`
- **RevPAR (Revenue Per Available Room)**: `Total revenue / Total rooms available`

### Daily Room Metrics

- **DBRN (Daily Booked Room Nights)**: Average rooms booked per day.
- **DSRN (Daily Sellable Room Nights)**: Average rooms available per day.
- **DURN (Daily Utilized Room Nights)**: Average rooms utilized per day.

### Week-over-Week (WoW) Changes

- **Revenue WoW Change %**: Percentage change in revenue from the previous week.
- **Occupancy WoW Change %**: Percentage change in occupancy from the previous week.
- **ADR WoW Change %**: Percentage change in ADR from the previous week.
- **RevPAR WoW Change %**: Percentage change in RevPAR from the previous week.
- **Realization WoW Change %**: Percentage change in realization from the previous week.
- **DSRN WoW Change %**: Percentage change in DSRN from the previous week.

## Conclusion

The Power BI dashboard provides stakeholders with a detailed view of hotel performance from various perspectives—city, room class, booking platform, and more. The visualizations facilitate insights into revenue generation, occupancy rates, booking behavior, and customer satisfaction, empowering hotel managers to make informed decisions for optimizing performance.

