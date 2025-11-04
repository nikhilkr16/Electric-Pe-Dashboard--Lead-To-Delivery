# ⚡ ElectricPe Lead-to-Delivery Funnel Analysis & Dashboard

This project analyzes and visualizes ElectricPe’s lead journey from generation to delivery across multiple Mobility Business Centers (MBCs).  
It tracks key operational metrics, identifies high-potential leads, and provides actionable insights through an interactive Excel dashboard.

---

## 📊 Project Overview

**Objective:**  
To analyze the sales funnel and delivery performance of ElectricPe stores and build a data-driven dashboard that helps management optimize lead conversions and operational efficiency.

**Data Source:**  
- File: `Nikhil_Kumar_BTECH1088322.xlsx`  
- Sheets: `RAW DATA`, `HELPER`, `ChartData`, `Dashboard`

---

## 🔍 Key Metrics Analyzed

| Metric | Description |
|---------|--------------|
| **Total Leads** | Count of all incoming customer leads |
| **Deliveries** | Total successful vehicle deliveries |
| **Cancellations** | Leads lost due to various reasons |
| **Conversion Rate** | % of leads that converted into deliveries |
| **Average TAT (Turnaround Time)** | Avg. time between lead to booking and booking to delivery |
| **Average NPS (Net Promoter Score)** | Overall customer satisfaction rating |
| **Hot/Warm/Cold Lead Distribution** | Lead temperature based on activity and status |

---

## 📈 Dashboard Insights

### 1️⃣ Lead Conversion Funnel by Store
- Visualizes drop-off at each stage: Lead → Pre-Booking → Booking → Delivery
- Filterable by **Store Name**

### 2️⃣ TAT Performance by Stage
- Compares average turnaround time for Pre-Booking, Booking, and Delivery stages

### 3️⃣ Cancellation Trends
- Identifies top reasons for lead cancellations

### 4️⃣ Customer Rating Distribution
- Breaks down customer sentiment into Promoter, Passive, and Detractor segments

### 5️⃣ Hot/Warm/Cold Lead Segmentation
- Displays the lead distribution based on engagement and progress

---

## 🚦 High-Potential Lead Identification

A **“High Potential”** lead is identified using the formula:

```excel
=IF(AND(NOT(ISBLANK([@[Pre-Booking Date]])), ISBLANK([@[Delivery Date]]), [@[TAT Booking (Days)]]<=3), "High Potential", "Normal")



Criteria:

Pre-Booking done ✅

Delivery pending 🚫

Fast movement (TAT ≤ 3 days) ⚡

🎨 Dashboard Design Choices
Element	Style	Color
Background	Light Gray	#F5F5F5
Header Gradient	Electric Green → Lime	#00C853 → #64DD17
KPI Box Background	Subtle Light Green	#E8F5E9
Text	Dark Charcoal	#212121
Chart Background	White	#FFFFFF
Accent Colors	Blue #0078D4, Orange #FF8C00, Green #22A55B	

Font: Segoe UI / Montserrat
Theme: Clean, Modern, Executive

⚙️ Tools Used

Microsoft Excel – Data cleaning, analysis, and dashboard creation

Pivot Tables & Slicers – Interactive filtering and KPI generation

Conditional Formatting – Highlighting high-potential leads

Power Query – Data transformation and cleaning

📁 Repository Structure
📂 ElectricPe-Dashboard
│
├── 📊 Nikhil_Kumar_BTECH1088322.xlsx       # Main project Excel file
├── 📝 README.md                            # Documentation (this file)
├── 📸 Screenshots/                         # Dashboard visuals
│   ├── dashboard_overview.png
│   ├── funnel_view.png
│   └── cancellation_trends.png
└── 📄 License (optional)

🧠 Insights & Learnings

Faster TAT correlates directly with higher lead conversion rates

Most cancellations are due to price sensitivity or model unavailability

Stores with higher NPS also have better booking-to-delivery ratios

🚀 How to Use

Open the Excel file Nikhil_Kumar_BTECH1088322.xlsx

Navigate to the Dashboard sheet

Use the Store Name slicer to filter results by location

Explore KPIs, charts, and insights interactively

👨‍💻 Author

Nikhil Kumar
🎓 B.Tech (10883/22)
💼 Data Analytics | Business Intelligence | Dashboard Design
📧 [Add your email or LinkedIn URL here]
