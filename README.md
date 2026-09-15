# Hospitality / Hotel Dashboard

This repository showcases a Power BI project analyzing hotel booking and revenue data to derive actionable insights and present them through an interactive dashboard.

## Project Description

The **Hospitality Dashboard** analyzes hotel operations data — bookings, room inventory, and property details — across multiple properties, cities, and room classes. The objective was to track key hospitality performance metrics (revenue, occupancy, pricing, and booking behavior) over time and support data-driven decision-making for property managers.

## Tools and Technologies Used

- **Power BI**: For data modeling, DAX measures, and dashboard creation.
- **DAX**: For calculated KPIs (Revenue, RevPAR, ADR, Occupancy %, etc.).
- **CSV/Relational Data**: Fact and dimension tables (star schema).

## Data Model

The dashboard is built on a star schema with the following tables:

| Table | Description |
|---|---|
| `fact_bookings` | Booking-level transactional data (includes booking platform) |
| `dim_rooms` | Room details, including room class |
| `Dim_hotels` | Property details — property ID, name, city, category |
| `Dim_date` | Date dimension — week number, month-year, day type |
| `Key_measure_table` | Central table holding all DAX measures used across the report |

## Key Metrics (KPIs)

| Metric | Definition |
|---|---|
| **Revenue** | Total revenue generated |
| **RevPAR** | Revenue per Available Room |
| **ADR** | Average Daily Rate |
| **DSRN** | Daily Sellable Room Nights |
| **DBRN** | Daily Booked Room Nights |
| **DURN** | Daily Utilized Room Nights |
| **Occupancy %** | Percentage of available rooms occupied |
| **Total Bookings** | Total number of bookings made |
| **Cancellation %** | Percentage of bookings cancelled |
| **Realisation %** | Percentage of bookings actually realized (not cancelled) |
| **Average Rating** | Average guest rating across properties |
| **Revenue WoW change %** | Week-over-week change in revenue |

## Key Features

- Interactive KPI cards for Revenue, RevPAR, ADR, Occupancy %, Total Bookings, and more.
- Detailed property-level table with revenue, bookings, RevPAR, occupancy, ADR, DSRN, DBRN, and DURN by property.
- Trend analysis via line charts and a combo chart (line + stacked column) for revenue and booking metrics over time.
- Donut chart breakdown (e.g., by room class / booking platform).
- Slicers for filtering by date, city, room class, and other dimensions.
- A dedicated **tooltip page** showing a Revenue trend chart, displayed on hover for deeper context.

## Dashboard Preview

The dashboard can be viewed interactively by opening the provided Power BI file in Power BI Desktop.

## How to Use This Repository

1. Clone the repository to your local machine.
2. Open the `Hotel_Dashboard.pbix` file in Power BI Desktop.
3. Explore the dashboard interactively using the slicers and visuals.

## Repository Link

You can view the full project on GitHub: *[add your GitHub repository link here]*

## Credits

- YouTube Channel: *https://www.youtube.com/@codebasics*
- Project Video: * https://youtu.be/tT4V7zguCnc?si=VL5JYDA3vucL67Gz*

## Background Inspiration

Inspired by hospitality industry KPI reporting standards (RevPAR, ADR, Occupancy %) commonly used in hotel revenue management.

---

Feel free to explore, modify, and share this project. Contributions are welcome!
