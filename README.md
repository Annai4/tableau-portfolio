# ✈️ Operations Health: Airlines and Airports

The final capstone project of the Tableau module — an operational
dashboard analyzing flight delays and cancellations across US airlines
and airports for the Ministry of Transport.

🔗 **[View Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/hanna.ivanova/viz/IvanovaHannaProject_TableauGerman/OperationsHealthAirlinesandAirportsGerman)**

*Note: dashboard labels are in German, as this version was built for
German-language practice.*

## 📌 Project Overview
Scenario: working for the Ministry of Transport, analyze completed
flights across all airlines to compare airports and airlines against
each other, identify outliers by number of cancellations and delays,
find patterns, and propose improvements — for example, if certain
airports frequently experience delays due to late aircraft turnaround,
a potential solution could be adding buffer time to the schedule between
arrival and departure.

## 🎯 Features
- **KPI cards**: Total Flights, Average/Max Taxi Time (departure &
  arrival), System-wide Delay Rate, Flight Delay %, Critical Flights %,
  Active Fleet size, Average/Max Arrival & Departure Delay, number of
  Airlines
- **Monthly trend line** of average arrival/departure delays (≥15 min),
  with min/max values highlighted
- **Top 7 impact ranking** by airport (ORD, DFW, SEA, RDU, CVG, etc.) and
  by airline, showing total flights, delayed flights, and critical delays
- **Cancellation Reason breakdown** (Airline/Carrier, Weather, National
  Air System) shown as a % of total cancellations — revealing that
  weather is the single largest cause of cancellations in this dataset
- **Adjustable delay threshold parameter** (e.g. 15 min, 60 min) to
  redefine what counts as a "delayed" flight across the whole dashboard
- **Interactive filters**: delay type (departures/arrivals), delay
  threshold

## 🛠️ Tech Stack
- Tableau Public
- Flight dataset (Flights, Airlines, and Airports tables, joined by
  airline and airport codes)

## 💡 What I Learned
- Building a dashboard from a technical specification with mandatory
  requirements (KPIs, timeline, dual axes, parameters used instead of
  filters)
- Joining multiple related tables into a single data model using
  physical joins
- Designing parameters as dashboard-wide toggles instead of relying only
  on filters
- Translating raw categorical codes (e.g. cancellation reason codes)
  into clear, labeled visualizations so the dashboard is understandable
  without external documentation

## 📸 Preview
![Dashboard preview](screenshot.png)
