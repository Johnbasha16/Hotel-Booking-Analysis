# Hotel Booking Analysis

## Project Overview

This project focuses on data cleaning and exploratory data analysis of a hotel booking dataset using Python.

The analysis explores booking patterns, cancellations, customer types, market segments, pricing, stay duration, and other important factors related to hotel bookings.

## Objectives

- Clean and preprocess the hotel booking dataset
- Handle missing values
- Remove duplicate records
- Convert data types appropriately
- Detect and treat numerical outliers
- Perform exploratory data analysis
- Identify important trends and patterns
- Export the cleaned dataset

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset

The project uses an open-source Hotel Booking Demand dataset containing information about hotel reservations, customers, booking channels, cancellations, stay duration, and pricing.

## Data Cleaning

The following preprocessing steps were performed:

- Handled missing values
- Removed duplicate records
- Converted date columns to datetime format
- Detected outliers using the IQR method
- Applied outlier capping to selected numerical columns

## Exploratory Data Analysis

The project analyzes:

- Hotel type distribution
- Booking cancellation behavior
- Market segment distribution
- Customer types
- Average Daily Rate (ADR)
- Booking lead time
- Stay duration
- Correlation between numerical variables
- Cancellation rates
- Monthly booking trends
- Distribution channels
- New vs repeated guests
- Meal preferences
- Parking requirements
- Arrival-day patterns

## Key Insights

- City Hotel received the highest number of bookings.
- The overall cancellation rate was approximately 13.55%.
- Groups had the highest cancellation rate among the analyzed market segments.
- BB (Bed & Breakfast) was the most common meal type.
- Transient was the most common customer type.
- The average ADR was approximately 112.71.
- The average booking lead time was approximately 74 days.
- The average total stay duration was approximately 3 nights.

## Project Files

- `Hotel_Booking_Analysis.ipynb` — Complete data cleaning and EDA notebook
- `cleaned_hotel_booking.csv` — Cleaned dataset

## Conclusion

This project demonstrates practical skills in data cleaning, preprocessing, exploratory data analysis, and data visualization using Python and its major data analysis libraries.
