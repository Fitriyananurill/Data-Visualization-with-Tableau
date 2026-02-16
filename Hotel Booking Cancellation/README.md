# Hotel Booking Cancellation Analysis – Tableau Dashboard

![Dashboard Preview](Dashboard%20Image.png)

1️⃣ Project Background

This project analyzes hotel booking data to understand cancellation behavior, booking patterns, customer segmentation, and revenue-related indicators. The objective is to transform raw booking records into an interactive Tableau dashboard that helps management identify cancellation drivers and optimize booking strategies.

2️⃣ Objectives

- Measure overall cancellation rate
- Identify monthly cancellation trends
- Analyze cancellation behavior by market segment
- Evaluate impact of deposit type on cancellation
- Understand lead time distribution
- Examine relationship between lead time and ADR

3️⃣ Link Data Source: [Click here](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

4️⃣ Dashboard Components & Design Logic

1. KPI Cards

- Total Booking: 119,390
- Total Cancelled: 44,224
- Cancellation Rate: 37.04%
- Avg Lead Time: 104 days
- Avg ADR: 99.06
- Designed to provide executive-level overview of booking performance and cancellation magnitude.

2. Booking Cancellation Distribution (Donut Chart)

- 37.04% bookings cancelled
- 62.96% successfully completed
- Purpose: Highlight scale of revenue risk due to cancellations.

3. Cancellation Trend per Month (Line Chart)

- Cancellation rate fluctuates between ~30%–42%
- Peaks observed around April–June
- Drops toward end of year
- Purpose: Identify seasonal cancellation patterns.

4. Cancellation by Market Segment & Deposit (Heatmap Table)

- Online TA shows highest cancellation rate under No Deposit (~36.64%)
- Non-Refund deposit significantly reduces cancellation in most segments
- Groups segment shows extreme dependency on deposit type
- Purpose: Understand behavioral differences across customer acquisition channels.

5. Lead Time Distribution (Histogram)

- Majority bookings made within 0–60 days before arrival
- Long lead times (>300 days) are relatively rare
- Purpose: Evaluate booking planning behavior.

6. Lead Time vs ADR (Scatter Plot)

- Weak negative relationship observed
- Higher lead time does not consistently correspond to higher ADR
- Outliers exist at extreme lead times
- Purpose: Assess pricing behavior relative to booking window.

5️⃣ Key Findings

1. Cancellation rate is significantly high at 37.04%, indicating substantial revenue volatility risk.
2. Online Travel Agents (OTA) contribute the highest cancellation proportion (~36.6% under no deposit).
3. Non-refundable deposit policy strongly reduces cancellation probability across most segments.
4. Cancellation peaks mid-year, suggesting possible seasonal overbooking or demand fluctuation.
5. Average lead time of 104 days indicates customers plan bookings relatively early, yet cancellations remain high.

🧠 Skills Demonstrated

Data Visualization • KPI Modeling • Cancellation Rate Analysis • Market Segmentation Analysis • Behavioral Pattern Detection • Interactive Dashboard Design • Tableau Development • Analytical Storytelling
