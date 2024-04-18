
# 📊 Hospitality Data Analysis Project

![Hospitality Data Analysis](images/hospitality_data_analysis.jpg)

## Overview
Welcome to the Hospitality Data Analysis Project! This repository contains code snippets and calculations for a comprehensive analysis of hospitality data. Our project focuses on exploring various metrics and insights crucial for understanding revenue, occupancy, booking behavior, and performance trends in the hospitality industry.

## Data Description

### dim_date
- date: Dates present in May, June, and July.
- mmm yy: Date in the format of mmm yy (monthname year).
- week no: Unique week number for each date.
- day_type: Whether the day is Weekend or Weekday.

### dim_hotels
- property_id: Unique ID for each hotel.
- property_name: Name of each hotel.
- category: Class (Luxury, Business) the hotel belongs to.
- city: Location of the hotel.

### dim_rooms
- room_id: Type of room (RT1, RT2, RT3, RT4) in a hotel.
- room_class: Class (Standard, Elite, Premium, Presidential) the room type belongs to.

### fact_aggregated_bookings
- property_id: Unique ID for each hotel.
- check_in_date: Check-in dates of customers.
- room_category: Type of room (RT1, RT2, RT3, RT4) in a hotel.
- successful_bookings: Number of successful room bookings for a room type on a particular date.
- capacity: Maximum count of rooms available for a room type on a particular date.

### fact_bookings
- booking_id: Unique Booking ID for each customer.
- property_id: Unique ID for each hotel.
- booking_date: Date when the customer booked their rooms.
- check_in_date: Date when the customer checked in at the hotel.
- check_out_date: Date when the customer checked out of the hotel.
- no_guests: Number of guests who stayed in a room.
- room_category: Type of room (RT1, RT2, RT3, RT4) in a hotel.
- booking_platform: Way the customer booked their room.
- ratings_given: Ratings given by the customer for hotel services.
- booking_status: Whether the booking was Cancelled, Checked Out, or No Show.
- revenue_generated: Amount of money generated by the hotel from a customer.
- revenue_realized: Final amount of money that goes to the hotel based on booking status.

## Key Metrics and Calculations
Explore various key metrics and calculations included in our analysis, such as total revenue realized, occupancy percentage, average daily rate (ADR), and more.



