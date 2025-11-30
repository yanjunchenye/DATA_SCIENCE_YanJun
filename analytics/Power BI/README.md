# 🥐 Bakery Sales Analytics Dashboard

## 📊 Project Overview
This project performs an end-to-end analysis of transactional data from a retail bakery. The primary objective was to transform raw sales data into a Business Intelligence system to optimize daily production, manage staff shifts, and understand consumer behavior.

The result is an interactive **Power BI** dashboard that enables management to transition from intuition-based to data-driven decision-making.

## 💼 Business Problem & Solution
**The Challenge:** The bakery operated with uncertainty regarding daily baking quantities and staffing schedules, leading to operational waste (shrinkage) and lost sales due to stockouts.

**The Solution:** A robust data model that answers critical business questions:
1. When is the real "operational peak hour"?
2. Which products act as "hooks" for cross-selling?
3. How does consumption behavior differ between weekdays and weekends?

## 🔍 Key Insights
After analyzing the data, the following patterns were detected:
* **The "Brunch" Phenomenon:** Contrary to the popular belief that bakeries sell the most at breakfast (8:00 AM), data reveals the peak transaction volume occurs between **10:00 AM and 12:00 PM**, particularly on Saturdays.
* **Product Strategy:** **Coffee** is the undisputed leader, appearing in over 50% of tickets. Any marketing strategy should pivot around it.
* **Weekly Patterns:** **Weekend** business volume is double that of weekdays, justifying a differentiated inventory planning strategy.

## 🛠️ Tech Stack & Methodology
This project demonstrates mastery of the following technical competencies:

* **ETL (Power Query):**
    * Cleaning raw data.
    * Fixing source errors (re-calculating mislabeled weekdays/weekends from the original CSV).
    * Table normalization.
* **Data Modeling:**
    * **Star Schema** design.
    * Creation of a dynamic **Date Table** using DAX.
    * Optimized One-to-Many relationships.
* **Advanced DAX:**
    * Explicit measures for KPIs (`DISTINCTCOUNT`, `CALCULATE`, `DIVIDE`).
    * Safety logic to handle division-by-zero errors.
    * Time Intelligence functions for weekly comparisons.
* **Data Visualization & UX:**
    * App-like interface design with page navigation.
    * **Heatmaps** for temporal analysis.
    * Implementation of **AI Visuals** (Decomposition Tree) for root cause analysis.
    * Smart Narrative for automatic executive summaries.


## 🚀 How to use
1.  Download the `Bakery_Sales_Analysis.pbix` file from this repository.
2.  Open the file in **Power BI Desktop**.
3.  Interact with the top filters to segment by "Weekend" or "Weekday".
4.  Navigate between pages using the custom buttons in the header.