# Hotel Booking Cancellation Prediction & Revenue Risk

A machine learning project developed during a hackathon to predict hotel booking cancellations and identify factors that contribute to cancellation risk.

The project uses the Hotel Booking Demand dataset and applies data analysis, feature engineering, and machine learning to help hotels identify potentially risky bookings early and make better occupancy and revenue decisions.

---

## Project Overview

Hotel cancellations can lead to:

- Empty rooms
- Lost revenue
- Inefficient occupancy planning
- Difficulty managing hotel resources
- Increased dependency on last-minute bookings

The objective of this project is to answer three key questions:

1. Which bookings are likely to be cancelled?
2. What factors contribute to cancellation risk?
3. How can hotels use these predictions to reduce potential revenue loss?

---

## Business Objective

The goal is not only to predict cancellations but also to convert the predictions into actionable business insights.

A hotel could use cancellation-risk predictions to:

- Prioritize high-risk bookings for confirmation
- Improve occupancy forecasting
- Apply appropriate deposit/payment strategies
- Identify customers with a history of cancellations
- Take early action to refill rooms
- Reduce potential revenue loss

---

## Dataset

The project uses the **Hotel Booking Demand Dataset**.

Dataset size:

- Approximately 119,390 bookings
- 32 original features
- Target variable: `is_canceled`

### Target Variable

| Value | Meaning |
|---|---|
| `0` | Booking was not cancelled |
| `1` | Booking was cancelled |

### Important Features

Some of the important variables include:

- `hotel`
- `lead_time`
- `arrival_date_year`
- `arrival_date_month`
- `arrival_date_week_number`
- `arrival_date_day_of_month`
- `stays_in_weekend_nights`
- `stays_in_week_nights`
- `adults`
- `children`
- `babies`
- `meal`
- `country`
- `market_segment`
- `distribution_channel`
- `is_repeated_guest`
- `previous_cancellations`
- `previous_bookings_not_canceled`
- `reserved_room_type`
- `assigned_room_type`
- `booking_changes`
- `deposit_type`
- `customer_type`
- `adr`
- `total_of_special_requests`

---

# Project Workflow

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Leakage Detection
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
Train/Test Split
     ↓
Data Preprocessing
     ↓
Model Training
     ↓
Model Comparison
     ↓
Model Evaluation
     ↓
Feature Importance
     ↓
Revenue Risk Analysis
     ↓
Business Recommendations
