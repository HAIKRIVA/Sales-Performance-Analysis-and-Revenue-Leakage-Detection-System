# 📈 Sales Performance Analysis and Revenue Leakage Detection System

A comprehensive sales analytics and revenue recovery system that combines a Python analytics engine with an interactive web-based dashboard to identify sales trends and pinpoint sources of revenue leakage.

---

## 🌟 Key Features

### 1. Revenue & Sales Analytics
- **Order Metrics**: Tracks total volume of orders, gross revenue, and net profit.
- **Regional Performance**: Compares revenue contributions across geographical zones (North, South, East, West).
- **Product & Monthly Trends**: Monitors product performance and monthly revenue trajectories.

### 2. Revenue Leakage Detection
- **Discount Leakage**: Identifies loss from excessive discounting.
- **Return Leakage**: Quantifies value lost to returned merchandise.
- **Stock Loss Leakage**: Highlights inventory loss and leakage during warehousing/fulfillment.
- **Total Revenue Leakage**: Summarizes all leakages to identify profit-recovery opportunities.

### 3. Interactive Web Application
- **Smart Revenue Recovery Dashboard**: Rich browser-based interface (`index.html`) featuring visual KPI cards, EmailJS alerting integration, and interactive recovery workflows.

---

## 📁 Project Structure

```text
├── sale.py              # Core Python sales and leakage analysis script
├── sales_data.csv       # Primary dataset containing sales transactions
├── saledata.csv         # Original CSV data
├── index.html           # Interactive web application dashboard
├── Web Application      # Standalone web app markup
├── .gitattributes       # Git line-ending attributes
└── README.md            # Project documentation
```

---

## 🚀 Getting Started

### 1. Run Python Analytics Engine
Ensure Python 3 is installed:
```bash
python sale.py
```
*(On Windows systems with Python 3 launcher, run `py -3 sale.py`)*

### 2. Launch the Web Application
Simply open `index.html` in any modern web browser:
- Double-click `index.html` or open via browser (`Chrome`, `Edge`, `Firefox`).
