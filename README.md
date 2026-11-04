# Uber-Ride-Mobility-Analytics

# Uber Ride & Mobility Analytics

An end-to-end data analytics project focused on analyzing Uber ride bookings, customer behavior, vehicle performance, cancellations, and mobility patterns using Python and its data analysis libraries.

## Project Overview

This project analyzes **150,000 Uber ride booking records** to uncover meaningful insights into ride demand, booking patterns, customer cancellations, driver performance, and operational efficiency.

The objective is to transform raw ride-booking data into actionable business insights through data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization.

## Project Objectives

- Analyze overall ride-booking performance.
- Identify peak booking hours and demand patterns.
- Understand customer and driver cancellation behavior.
- Analyze vehicle-type preferences.
- Examine pickup and drop-off location patterns.
- Investigate incomplete rides and their reasons.
- Identify operational inefficiencies.
- Generate actionable recommendations for improving mobility services.

## Dataset Information

| Attribute | Details |
|---|---|
| Dataset | Uber Ride Bookings |
| Total Records | 150,000 |
| Total Columns | 21 |
| Data Type | CSV |
| Domain | Transportation & Mobility Analytics |
| Difficulty | Intermediate |

### Key Dataset Columns

- Date, Time
- Booking ID, Booking Status
- Customer ID
- Vehicle Type
- Pickup Location, Drop Location
- Avg VTAT, Avg CTAT
- Cancelled Rides by Customer
- Reason for cancelling by Customer
- Cancelled Rides by Driver
- Driver Cancellation Reason
- Incomplete Rides
- Incomplete Rides Reason

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Google Colab | Development environment |

## Project Workflow

1. **Data Collection:** Download and load the raw CSV dataset.
2. **Data Exploration:** Examine dimensions, columns, data types, and missing values.
3. **Data Cleaning:** Handle missing values, duplicates, inconsistent records, and incorrect data types.
4. **Feature Engineering:** Extract date and time features for demand analysis.
5. **Exploratory Data Analysis:** Investigate booking trends, cancellations, vehicle types, and ride performance.
6. **Data Visualization:** Create charts to communicate important findings.
7. **Business Insights:** Identify operational challenges and propose improvements.

## Key Analysis Areas

### 1. Booking Performance
- Total bookings
- Successful rides
- Cancelled bookings
- Incomplete rides
- Booking status distribution

### 2. Time-Based Analysis
- Hourly booking trends
- Daily booking patterns
- Monthly demand trends
- Peak mobility hours

### 3. Vehicle Analysis
- Bookings by vehicle type
- Vehicle popularity
- Vehicle-wise booking performance

### 4. Cancellation Analysis
- Customer cancellation rate
- Driver cancellation rate
- Cancellation reasons
- Factors affecting ride completion

### 5. Operational Analysis
- Average Vehicle Time of Arrival (VTAT)
- Average Customer Time of Arrival (CTAT)
- Incomplete ride analysis
- Operational efficiency












## Installation

Clone the repository:

```bash
git clone https://github.com/Ghost-Ashish/Uber-Ride-Mobility-Analytics.git
```

Navigate to the project directory:

```bash
cd Uber-Ride-Mobility-Analytics
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Requirements

```text
pandas
numpy
matplotlib
seaborn
jupyter
```

## Business Impact

The analysis aims to help mobility platforms:

- Improve ride availability during peak hours.
- Reduce customer and driver cancellations.
- Understand vehicle demand and allocation.
- Improve operational efficiency.
- Identify patterns behind incomplete rides.
- Support data-driven transportation decisions.

## Future Enhancements

- Integrate PostgreSQL for advanced SQL-based analytics.
- Develop an interactive Power BI dashboard.
- Build predictive models for ride demand forecasting.
- Analyze cancellation patterns using machine learning.
- Develop a mobility performance monitoring dashboard.

## Author

**Ashish Kumar Gupta**

B.Tech Computer Science & Engineering

University of Lucknow

- GitHub: [Ghost-Ashish](https://github.com/Ghost-Ashish)
- LinkedIn: [Ashish Kumar Gupta](https://www.linkedin.com/in/ashish-kumar-gupta-ghostashish/)

---

⭐ If you find this project useful, consider giving the repository a star.

*This project is developed for educational purposes and demonstrates practical data analytics skills using Python.*
