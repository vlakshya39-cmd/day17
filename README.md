# day17
# Day 17: Vehicle Cost Analysis Dashboard 🚗📊

## Project Overview
For Day 17 of the challenge, I built an interactive, responsive **Vehicle Cost Analysis Dashboard** using data analysis and frontend web technologies. The project profile is tailored to a **Honda City (1.5L i-VTEC, Petrol, 3 Years Old)** with an average monthly usage of **1,200 km**.

The dashboard calculates key metrics by grouping dataset records by fuel types (CNG, Diesel, E85, EV, and Petrol) to evaluate the financial and environmental impacts of different energy sources.

---

## Key Technical Implementations
* **Data-Driven Analysis:** Processed real-world vehicle dataset records to calculate exact per-kilometer costs, maintenance expenses, and average tailpipe $\text{CO}_2$ emissions.
* **The E85 Paradox Evaluation:** Computed the break-even pump price formula to reveal why a fuel that is 18% cheaper at the pump (E85) actually costs **3.6% more per kilometer** to run due to lower caloric efficiency/mileage.
* **Custom SVG Data Visualizations:** Designed and coded inline SVG charts from scratch, including a responsive cost-per-km bar chart, a $\text{CO}_2$ distribution doughnut chart with interactive hover tooltips, and a dynamic vehicle age-degradation line graph.
* **Modern UI Development:** Styled a sleek, responsive dashboard using a dark-navy glassmorphism theme, CSS-animated gauges, and localized glow highlights for the target vehicle profile.

---

## Key Insights & Findings
1. **The Cost King:** **EV** remains the cheapest mode of transport by a wide margin at **₹1.75/km**, followed by **CNG at ₹3.32/km**.
2. **The E85 Break-Even:** While E85 is cheaper per liter (₹82 vs ₹100 Petrol), its break-even price point for this vehicle profile must drop below **₹79.11/L** to make economic sense.
3. **Age Degradation:** Maintenance costs show a sharp upward trajectory as vehicles move from Mid-Life (3–5 years) to Aged (6–9 years), jumping from **₹0.56/km to ₹0.65/km**, and spiking drastically past 10 years.

---

## Repository Artifacts
* `dashboard.html`: The complete interactive dashboard file containing all inline CSS styles, SVG structures, and JavaScript tooltip interactions.
