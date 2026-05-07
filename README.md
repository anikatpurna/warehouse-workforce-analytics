# humano Workforce Intelligence

A data analytics prototype built for humano LLC — a Southern California logistics 
staffing company operating on a Cost-Per-Unit (CPU) model. This notebook demonstrates 
what a data intelligence layer could look like when built on top of humano's existing 
operations.

Built by Anika | University of Redlands — Data Science & Business Administration, Class of 2026

---

## What this project does

Most logistics staffing companies run on gut instinct and spreadsheets. This prototype 
shows how a lightweight analytics layer can turn raw operational data into actionable 
insights — helping humano reduce costs, retain workers, and outcompete larger players 
like Capstone Logistics.

---

## The 4 tools inside

**1. CPU Savings Calculator**
An interactive slider tool for humano's sales team. Input a client's warehouse size, 
hourly wage, and idle time — and instantly see exactly how much money they save by 
switching to humano's cost-per-unit model.

**2. Site Performance Dashboard**
A real-time operations view showing fill rate, CPU cost vs target, weekly units 
completed, and turnover risk across all humano sites in Southern California — 
color coded so managers know in seconds which sites need attention.

**3. Turnover Risk Predictor**
A predictive model that flags which workers are likely to quit before they actually do, 
using signals like shift attendance, scan rate, tenure, and late arrivals. Each worker 
is plotted on an interactive scatter chart scored from low to high risk.

**4. Competitor Gap Analysis**
A radar chart comparing humano directly against Capstone Logistics across six capability 
dimensions — showing exactly where the gaps are and where humano already wins.

---

## Tech stack

- Python
- Jupyter Notebook
- Plotly — interactive charts
- ipywidgets — live sliders
- Pandas — data manipulation
- NumPy — data simulation

---

## How to run it

1. Clone the repo
2. Open your terminal and run `jupyter notebook`
3. Open `humano_workforce_intelligence.ipynb`
4. Click **Kernel → Restart & Run All**

Or open it directly in Google Colab — no installation needed.

---

## Data disclaimer

All data in this notebook is completely simulated and does not represent real humano LLC 
operational data, employees, clients, or financial figures. Site names reflect real SoCal 
logistics hubs to make the demo geographically relevant. Metric ranges are grounded in 
publicly reported industry benchmarks for warehouse staffing operations.

The purpose of this prototype is to show what a data intelligence layer could look like 
once connected to humano's real operational data.

---

## About

This project was built in a single day as a demonstration of what data engineering 
and analytics could look like inside a logistics staffing company with no current 
analytics infrastructure. Every tool in this notebook addresses a real business problem 
humano faces today.

*University of Redlands · Data Science & Business Administration · Class of 2026*
