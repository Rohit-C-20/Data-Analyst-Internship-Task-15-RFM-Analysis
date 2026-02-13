# Task 15 - Customer Segmentation (RFM Analysis)

## Dataset Used
Online Retail Dataset

## Objective
Perform RFM (Recency, Frequency, Monetary) analysis to segment customers based on purchasing behavior.

## Steps Performed
- Removed cancelled invoices and null customer IDs
- Converted InvoiceDate to datetime
- Created TotalAmount column
- Calculated Recency, Frequency, Monetary values
- Applied quantile-based scoring
- Assigned customer segments (Champions, Loyal, At Risk, Regular)
- Visualized segment distribution
- Exported segmentation results to CSV

## Deliverables
- task15_rfm.ipynb
- rfm_segments.csv
- segment_actions.txt
