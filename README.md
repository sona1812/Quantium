# Quantium Virtual Data Analytics Internship

## Objective
To analyze customer transaction data in order to uncover sales patterns, customer preferences, and brand performance by segmenting consumers based on their demographics and purchasing behavior and which brands or pack sizes they prefer—supporting the Category Manager’s strategic planning for targeted marketing, product assortment, and promotion strategies for the chip category in the upcoming half-year.

## Tools and Libraries Used
* Pandas – data manipulation, cleaning, and aggregation
* Numpy – numerical operations and handling missing/outlier values
* Matplotlib – plotting bar charts and line graphs
* Seaborn – enhanced statistical visualizations (e.g.,countplots,scatterplpot)
* Datetime – handling and extracting date information (e.g., months)

## Concepts Used
* **Data Cleaning & Transformation**: Used pandas for merging datasets, grouping data, handling missing values, and calculating aggregates like total sales and average quantity.
* **Feature Extraction with String & Regex**: Extracted brand names and packet sizes from product descriptions using .str.extract() and regular expressions for deeper analysis.
* **Outlier Detection**: Applied the IQR method to detect and remove outliers from TOT_SALES, ensuring clean and accurate analysis.
* **Time Series Analysis**: Converted Excel date formats using pd.to_datetime() and performed monthly trend analysis with .dt.month and .groupby().
* **Data Visualization**: Created visual insights using matplotlib and seaborn (bar charts, line graphs, count plots) to compare customer segments, sales trends, and brand performance.

## Conclusion and Recommendations 
* **Mainstream customers and Old age Couples/Singles Families** contribute the most to total chip sales and show a preference for larger pack sizes.
  **Recommendation:** Launch targeted promotions and provide free Home delivery esp. for old age ones to boost the sales at these segments.
* **March** saw the highest spike in sales, likely due to seasonal factors or promotions.
  **Recommendation:** Align major campaigns and discount offers around March to capitalize on demand.
* There is a **moderate positive correlation (r = 0.31)** between packet size and total sales.
  **Recommendation:** Consider bundling or upsizing strategies to increase average transaction value.
* Brands like **Kettle, Smiths, Doritos, and Pringles** dominates overall sales.
  **Recommendation:** Ensure these popular brands are available across all distribution channels, including online and in smaller convenience stores, as they likely have a strong customer base.


