# Sales Business Analytics (pandas · NumPy · Seaborn · Matplotlib)

## Overview :
This project analyzes 1,000 sales records to uncover business insights:
- Monthly trends in Revenue and Profit
- Average Profit Margin by Region
- Sales patterns via heatmap (Region vs Time)
- Relationship between Revenue and Profit Margin
- Cumulative Revenue trend
- Revenue distribution per Sales Channel

## Dataset :
The data is loaded from a GitHub URL in the notebook.  
No missing values noted — data is clean and ready for analysis.

## Repository Structure :
data/
└── sales_records.csv
notebook/
└── analysis_notebook.ipynb
outputs/
├── overall_stats.csv
├── monthly_summary.csv
├── region_profit_margin.csv
├── units_sold_trend.csv
└── cumulative_revenue.csv
figures/
├── monthly_revenue_trend.png
├── profit_margin_by_region.png
├── units_sold_heatmap.png
├── revenue_margin_scatter.png
├── cumulative_revenue_curve.png
└── revenue_by_channel_box.png
README.md
LICENSE

bash

## How to Run :
```bash
pip install pandas numpy seaborn matplotlib
jupyter notebook notebook/analysis_notebook.ipynb

## Business Insights :

- Revenue trends help highlight high-performing months.
- Some regions have higher profitability.
- Heatmap shows regional sales spikes and seasonality.
- Scatter highlights revenue vs margin performance.
- Cumulative curve useful for goal tracking.
- Boxplot helps compare channel performance variance.

License
MIT License — feel free to reuse with credit.

