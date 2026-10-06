Data Analytics Internship – Task 29 (Product Basket Analysis)

This repository contains my submission for Task 29 of the Data Analytics Internship.

Dataset - Online Retail II Dataset

Objective - The objective was to identify products frequently purchased together and understand potential cross-selling and product-bundling opportunities.

Tools Used
1. Python
2. Pandas
3. Google Colab
4. GitHub

Product Basket Analysis
1. Used the Online Retail II Dataset containing 525,461 records.
2. Inspected the dataset for missing values, duplicates, data types, and product and invoice information.
3. Removed records with missing product descriptions, cancelled invoices, and invalid quantities or prices.
4. Removed duplicate rows from the cleaned dataset.
5. The cleaned dataset contained 504,730 records.
6. Grouped products by Invoice to identify products purchased within the same order.
7. Removed duplicate products within each invoice to prevent duplicate pair counts.
8. Generated combinations of two different products from each invoice.
9. Counted how frequently each product pair appeared across orders.
10. Identified the Top 10 most frequently purchased product pairs.
11. Created recommendations for cross-selling and product bundling opportunities.

Key Results
1. Cleaned Records - 504,730
2. Invoices Analyzed - 20,951
3. Unique Product Pairs - 4,698,390
4. Top Product Pair - SWEETHEART CERAMIC TRINKET BOX and STRAWBERRY CERAMIC TRINKET BOX
5. Top Pair Frequency - 729 orders

Key Insights
1. The most frequently purchased product pair appeared together in 729 orders.
2. Cake-related products were among the frequently purchased product combinations.
3. Matching and complementary products were commonly purchased together.
4. Frequently paired products can provide useful cross-selling and bundling opportunities.
5. Product-pair analysis can help businesses understand purchasing patterns and improve product recommendations.

Files
1. Task 29.ipynb - Google Colab notebook containing data cleaning, product basket analysis, top product pairs, insights, and recommendations
2. Task 29.csv - CSV file containing the Top 10 frequently purchased product pairs
3. README.md - Summary of the product basket analysis

Conclusion
Product Basket Analysis was successfully performed using Python and Pandas. The analysis identified frequently purchased product combinations by grouping products based on Invoice IDs. The results highlighted several product pairs that could be used for potential cross-selling, product recommendations, and bundle offers.
