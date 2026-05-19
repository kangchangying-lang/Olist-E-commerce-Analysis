# Olist E-commerce Operational Performance Analysis
*Project Scope: 2017 - 2018 Data Analysis* 

*Key Metric: Order Volume vs. Cancellation Rate (%)*

---

## 1. Research Context & Discovery
Through exploratory analysis of Olist’s 2017-2018 datasets, I identified a critical trend worth investigating: the correlation between rapid business scaling and operational stability.

* **The Discovery:** Initial data inspection revealed a 10x growth in volume. I wanted to verify if this expansion triggered an increase in the **cancellation rate**.
* **Analytical Focus:** I developed a **Dual-Axis Dashboard** to confirm whether the logistics infrastructure remained resilient during peak periods.

## 📊 Key Visualization: Operational Health Dashboard
![Operational Dashboard](./dashboard_20260519.png)
*This chart correlates monthly order volume (stacked bars) with the cancellation rate (line with markers) to monitor scalability.*

## 2. Key Insights
* **Demonstrated Scalability:** Despite a 10x increase in total order volume, the Cancellation Rate remained within a stable range, indicating highly scalable operations.
* **Resilience Under Pressure:** During the Nov 2017 "Black Friday" peak, the Cancellation Rate (%) remained flat despite record-high volumes, proving logistics resilience.
* **Operational Maturity:** Comparing early 2018 to 2017, cancellation rates showed a downward trend at similar volumes, suggesting significant process optimization.

## 3. Next Steps (Root Cause Analysis)
To further optimize customer experience, I will perform:
* **Category Attribution:** Identify if high cancellation rates are concentrated in specific categories (e.g., heavy furniture).
* **Logistics Correlation:** Verify if "Estimated Delivery Time" delays drive "Customer Regret."
* **Geographic Analysis:** Identify underperforming regional logistics partners by state.

## 4. Tech Stack
* **Language**: Python
* **Libraries**: Pandas, Matplotlib, Seaborn
* **Environment**: Google Colab
