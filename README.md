This project analyzes e-commerce transaction data to understand pricing behavior, brand performance, and product category trends.

The analysis focuses on identifying:
	•	High-value brands
	•	Premium product categories
	•	Pricing vs selling price differences
	•	Discount patterns affecting profitability

  Data Extraction/Load

The raw datasets were loaded using Pandas and inspected for structure and missing values.

Key steps:
	•	Import CSV files
	•	Verify column formats
	•	Initial exploration of dataset structure


  Data Cleaning

  Cleaning steps include:
	•	Handling missing values in product names and descriptions
	•	Merging product and orderline datasets
	•	Mapping brand codes to brand names
	•	Creating product categories using keyword-based classification
	•	Generating time-based features such as:
	•	year
	•	month
	•	order_month

  
Data Analysis

  Key metrics analyzed:
	•	Top brands by average unit price
	•	Top product categories by average price
	•	Comparison of:
	•	List price
	•	Actual selling price
	•	Discount patterns across brands and categories

Aggregations were performed using Pandas groupby operations.


Viz.

Visualizations were created using Seaborn and Matplotlib.

Key charts include:
	•	Top 10 brands by average selling price
	•	Top 10 product categories by average price
	•	Price vs selling price comparisons
	•	Heatmaps for seasonal performance
	•	Color-coded bar charts to highlight pricing tiers

Findings

Some major findings from the analysis:
	•	Premium brands maintain higher average selling prices with smaller discount gaps.
	•	Certain product categories rely heavily on discounting to drive volume.
	•	Accessories and lower-price products tend to follow high-volume, lower-margin strategies.
	•	High-value product categories maintain stronger pricing power.

These insights help identify:
	•	Profit-driving product categories
	•	Discount-sensitive product segments
	•	Brand positioning opportunities

  Tools Used
  Python
	•	Pandas
	•	Matplotlib
	•	Seaborn
	•	Jupyter Notebook
	•	Git & GitHub
  
