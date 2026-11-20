 # FedEx Global Supply Chain Analytics Dashboard

## Project Overview
An interactive Power BI dashboard analyzing global supply chain delivery performance, shipment costs, vendor performance, and logistics efficiency.

**Tool:** Microsoft Power BI Desktop  
**Dataset:** SCMS_Delivery_History_Dataset  
**Records:** 10,324 line-item records  
**Unique Shipments:** 1,237

## Dashboard Pages

### 1. Executive Overview
- Key business performance indicators
- Shipment mode distribution
- Product value and freight cost trends
- Country-wise shipment analysis
- Product value by category

### 2. Delivery & Delay Performance
- On-time and delayed shipment analysis
- Average delivery delay
- Shipment mode delivery performance
- Yearly delivery trends
- Countries with the highest delayed shipments

### 3. Freight Cost & Vendor Analysis
- Total freight cost and freight cost percentage
- Freight cost by vendor Incoterms
- Freight cost by shipment mode
- Top vendors by freight cost
- Shipment weight versus freight cost analysis

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Unique Shipments | 1,237 |
| Total Line Item Value | $1.63bn |
| Total Freight Cost | $68.82M |
| Freight Cost % of Value | 4.23% |
| On-Time / Early Shipments | 76.64% |
| Delayed Shipments | 289 |
| Average Delay Days | -6.02 |
| Total Cargo Weight | 21.82M kg |
| Average Freight per Shipment | $55.63K |

## Data Preparation & Analysis
- Cleaned and transformed data using Power Query.
- Standardized date and shipment mode fields.
- Created calculated columns for delivery delay and delivery status.
- Developed DAX measures for shipment-level analysis and business KPIs.
- Used interactive slicers and cross-filtering across dashboard visuals.

## Key Insights
- Air is the dominant shipment mode, accounting for approximately 75.78% of shipments.
- 76.64% of unique shipments were delivered on time or early.
- Air freight has the highest freight cost percentage by shipment mode at 6.86%.
- SCMS from RDC is the highest freight-cost vendor at approximately $34.85M.
- Zambia leads the Top 10 Countries by Delayed Shipments visual.

## Recommendations
- Evaluate suitable non-urgent shipments for ocean or regional truck transportation.
- Improve customs clearance and delivery planning in countries with higher delays.
- Review vendor Incoterms and negotiate freight-cost efficiencies.
- Maintain priority logistics arrangements for critical shipments.

## Deliverables
- Power BI Dashboard (.pbix)
- Power BI Template (.pbit)
- Project documentation

## Conclusion
This project demonstrates how Power BI, Power Query, and DAX can transform supply chain data into actionable insights for logistics performance, delivery reliability, and freight-cost management.


## Dashboard Preview

### 1. Executive Overview
![Executive Overview](Page%201-Executive%20Overview.png)

### 2. Delivery & Delay Performance
![Delivery & Delay Performance](Page%202-Delivery%20and%20Delay%20Performance.png)

### 3. Freight Cost & Vendor Analysis
![Freight Cost & Vendor Analysis](Page%203-Freight%20cost%20and%20vendor%20Analysis.png)

