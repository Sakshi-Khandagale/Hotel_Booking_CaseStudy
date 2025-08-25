# Hotel Booking Case Study 🏨📊
## 📌 Description

This project analyzes hotel booking data to uncover patterns in customer behavior, cancellations, pricing, and seasonality. The goal is to help hotels improve operational efficiency, reduce cancellations, and grow revenue using data-driven insights.

## 🎯 Objectives

- Study booking patterns for city hotels vs resort hotels

- Identify factors influencing cancellations and pricing (ADR)

- Analyze seasonal, country-wise, and customer-type behavior

- Suggest strategies for revenue growth and better planning

## 📂 Dataset

The dataset contains 100K+ hotel bookings with details like:

Booking Information:

- hotel → City Hotel / Resort Hotel

- is_canceled → Whether the booking was canceled (0 = No, 1 = Yes)

- lead_time → Number of days between booking & arrival

- arrival_date_year, arrival_date_month, arrival_date_week_number, arrival_date_day_of_month

Stay Details:

- stays_in_weekend_nights, stays_in_week_nights

- adults, children, babies

Customer Information:

- country → Guest nationality

- is_repeated_guest, previous_cancellations, previous_bookings_not_canceled

- customer_type → Transient, Group, Contract, etc.

Booking Channel & Market:

- market_segment, distribution_channel

- agent, company

Room & Reservation:

- reserved_room_type, assigned_room_type, booking_changes

- deposit_type → No Deposit / Non Refund / Refundable

- days_in_waiting_list

- reservation_status, reservation_status_date

Pricing & Extras:

- adr → Average Daily Rate (price per night)

- meal, required_car_parking_spaces, total_of_special_requests

## 🛠 Methodology

- Data Cleaning → removed irrelevant columns, filled missing values, treated outliers

- EDA → univariate, bivariate, multivariate analysis

- Time Series Analysis → booking trends across months/years

- Correlation & Hypothesis Testing → validated assumptions statistically

## 📊 Key Insights

- City hotels had more bookings but also more cancellations

- Cancellations increase with longer lead times

- UK & France guests book earlier, Portuguese guests stay shorter

- Special requests linked with higher ADR (paying customers)

- Upgraded/reassigned rooms → fewer cancellations

- Corporate & direct bookings are more reliable

## 🧰 Tools & Libraries

- Python 🐍

- Pandas, NumPy → Data preprocessing

- Matplotlib, Seaborn → Visualization

- Jupyter Notebook → Analysis

## ✅ Conclusion

Hotels can optimize performance by:

- Adjusting pricing strategies based on lead time & customer type

- Planning staffing & marketing around seasonal peaks

- Offering room upgrades to reduce cancellations

- Targeting corporates and loyal customers for reliable revenue

## 📌 Future Scope

- Train ML models to predict cancellations

- Perform customer segmentation for marketing strategies

- Build real-time dashboards for hotel booking monitoring

---

## ✨ Developed by Sakshi Khandagale
