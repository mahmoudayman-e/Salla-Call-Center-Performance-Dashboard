# Salla Call Center Performance Dashboard (Power BI)

## 📌 Project Overview
This repository showcases an advanced, 4-page interactive **Call Center Performance Dashboard** built for **Salla (سلة)** using Power BI. The dashboard transforms complex customer support metrics into actionable operational insights. It allows call center managers to evaluate overall business efficiency, drill down into agent performance, audit daily operations, and run future resource planning simulations.

---

## 📷 Dashboard Screenshots & Core Features

### 1. Executive Dashboard (High-Level Overview)
<img width="1335" height="734" alt="Excutive" src="https://github.com/user-attachments/assets/da137e93-5631-4fc9-8d97-2c3b14fed60b" />

Provides senior leadership with a consolidated view of critical performance indicators (KPIs) and macro trends.
* **Top KPIs:** Total Calls (1.74M), Handling Ratio (98.7%), Service Level (91.1%), Abandonment Rate (1.3%), and Average Speed of Answer (ASA: 9.22).
* **Trend Analysis:** Visualizes Daily Call Volume fluctuations alongside monthly comparisons of Forecasted vs. Offered Calls.
* **Volume Distribution:** Breaks down calls by Day Name and Projects (Project A, B, C), and highlights the Top 10 Agents by Calls Handled.



---

### 2. Agent Performance Page (Granular Workforce Audit)
<img width="1353" height="741" alt="Agent" src="https://github.com/user-attachments/assets/7af3fde9-6a0a-48ae-b003-65a3010a34e7" />

Focuses entirely on employee productivity, output quality, and customer service delivery.
* **Performance Overview Matrix:** A comprehensive table sorting agents by Total Calls, Calls Handled, Handled Rate, Average ASA, and individual Abandonment Rates.
* **Agent Ranking Charts:** Includes horizontal bar charts comparing the exact sum of handled calls and Average ASA per Agent (e.g., tracking top performers like Dina and Tariq).



---

### 3. Operation Analysis Page (Operational Metrics)
<img width="1520" height="738" alt="Operation" src="https://github.com/user-attachments/assets/cf632b09-d166-42f5-9be6-4a78194eece9" />

Drives structural improvements by deep-diving into specific process bottlenecks across projects.
* **Project Breakdown:** Side-by-side bar chart comparisons tracking Service Level, Average ASA, and Abandonment Rate per project.
* **Monthly Aggregations:** Analyzes seasonal impacts by displaying Total Calls and Average Abandoned Calls by Month (February, March, April).
* **Operational Grid:** A unified Project Performance Summary matrix tracking numeric call volumes against forecasted expectations.



---

### 4. What-If Scenario Analysis Page (Predictive Modeling)
<img width="1037" height="577" alt="What if" src="https://github.com/user-attachments/assets/9d8efeb9-c05f-4995-ae10-33dce00dfafd" />

Demonstrates advanced technical capability by simulating operational capacity based on customer demand shifts.
* **Dynamic Parameter:** Features an interactive **Call Volume Increase (%)** slider ranging from 0% to 50%.
* **Predictive Forecasting:** Simulates `Projected Calls`, `Projected Handling Rate`, and `Projected Service Level` against baseline figures.
* **Capacity Planning:** Dynamically computes `Required Agents` and `Additional Agents Needed` to maintain service standards under higher call loads.



---

## 🛠️ Technical Toolkit & Advanced DAX Skills

* **What-If Parameters:** Implemented numeric range slicers linked with dynamic DAX models to run predictive workforce planning scenarios.
* **Advanced Data Modeling:** Standardized cross-filtering across 4 cohesive reporting canvases utilizing a corporate unified color map.
* **Dynamic Formatting:** Leveraged conditional indicators (Up/Down arrows) to clearly distinguish baseline targets from projected risk factors.
* **UX/UI Navigation:** Created a tailored left-hand vertical icon navigation menu bar (`Home`, `Grid`, `Headset`, `Trend`, `Filter`) mimicking a professional SaaS application interface.

---

## 🚀 How to Run the Project Locally
1. Clone this repository to your computer.
2. Ensure you have the latest version of **Power BI Desktop** installed.
3. Open the `.pbix` file within the repository root directory.
4. Use the custom sidebar filters (Project, Month, Agent Name) to slice across all operational views.
