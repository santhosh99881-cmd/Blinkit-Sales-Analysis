# Blinkit Sales Data Analysis

## Project Overview
This project performs a comprehensive analysis of sales data from Blinkit outlets. Using Python and data visualization libraries, it explores sales patterns across various dimensions such as product fat content, item category, outlet location tier, and outlet establishment year to derive actionable business insights.

## Dataset
- Source file: blinkit_data.csv
- Number of records: ~8,500+
- Number of features: 12

### Key Columns:
- Item Fat Content: Classification of the product fat content (Low Fat, Regular, etc.)
- Item Type: Product category (e.g., Fruits and Vegetables, Snack Foods)
- Outlet Establishment Year: Year when the outlet was established
- Outlet Location Type: Outlet classification by tier (Tier 1, Tier 2, Tier 3)
- Sales: Total sales amount

## Tools and Libraries Used
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## Methodology
1. Data Loading and Cleaning:
   - Loaded the Blinkit dataset using pandas.
   - Standardized categorical data inconsistencies, especially in the 'Item Fat Content' column.
   - Handled missing values and ensured data types were appropriate for analysis.

2. Exploratory Data Analysis:
   - Grouped data based on 'Item Fat Content' and 'Item Type' to evaluate sales contribution.
   - Analyzed sales trends by 'Outlet Establishment Year' and the effect of outlet location tier.
   - Visualized findings through bar charts and line graphs with markers.

## Key Insights
- Regular-fat products generate the highest total sales among fat content categories.
- Food-related categories like Fruits and Vegetables and Snack Foods are top revenue drivers.
- Outlets located in Tier 1 areas generally show better sales performance than those in Tiers 2 and 3.
- Sales trends over years by establishment reveal certain older outlets maintain strong and competitive sales.
  
## Conclusion
The findings emphasize the importance of focusing on high-performing product categories and premium outlet locations to maximize sales. Continuous monitoring of outlet performance and strategic marketing towards popular product types can further enhance revenue.

## How to Run
1. Install required Python libraries:
