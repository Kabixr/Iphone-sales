This project analyzes **online product sales activity by hour of the day** using Python, Pandas, and Matplotlib.

The core objective is to identify the **busiest hours (peak transaction times)** so that businesses can optimize:
- marketing campaigns,
- discount timings,
- inventory availability, and
- support staffing.

The analysis is based on an order-level dataset containing transaction timestamps and related information.

---

## 📁 Project Structure

```text
.
├── Order_details-masked.csv      # Input dataset (masked/anonymous order details)
├── sales_hour_analysis.ipynb     # Jupyter / Colab notebook with full analysis
├── hourly_counts.csv             # Output: number of transactions per hour (0–23)
├── transactions_per_hour.png     # Output: line chart of transactions across hours
└── README.md                     # Project documentation
