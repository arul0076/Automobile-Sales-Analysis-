# Automobile Sales Analysis

## Overview

This project involves analyzing automobile sales data to uncover trends, patterns, and insights into market dynamics and product performance. The analysis utilizes Python, focusing on exploratory data analysis (EDA) and data visualization techniques.

## Data

- **Dataset**: `Auto Sales data.csv`
- **Source**: [GitHub Repository](https://github.com/arul0076/Automobile-Sales-Analysis-/blob/dffd3171ed53e12eb6d630bc652495379f82d7e2/Auto%20Sales%20data.csv)
- **Description**: Contains sales records with attributes such as order dates, product categories, and sales figures.

## Data Characteristics

- **Entries**: 2,747 entries
- **Columns**: 20 columns
- **Missing Values**: All columns have 2,747 non-null values, indicating no missing values.
- **Key Columns**: Sales transaction details, customer information, product details, order status, recency information.
- **Data Types**: Floats, datetime, and objects.

## Import Libraries

The project uses the following Python libraries:
- `pandas` for data manipulation and analysis
- `matplotlib` and `seaborn` for data visualization

## Data Description

- **Sales Amount**: Average of approximately 3,553, ranging from 482.13 to 14,082.80.
- **Quantity Ordered**: Average of approximately 35 items per transaction, with a range from 6 to 97 items.
- **Price Each**: Average price of approximately 101, ranging from 26.88 to 252.87.
- **Manufacturer's Suggested Retail Price (MSRP)**: Average of approximately 100.69, with a range from 33 to 214.

## Analysis

### Univariate Analysis

- Sales amount, quantity ordered, price each, and MSRP are analyzed to understand their distributions and summary statistics.

### Bivariate Analysis

- **Order Status**: Most common status is "Shipped" (2,541 occurrences).
- **Product Line**: Dominant product line is "Classic Cars" (949 entries).
- **Customer Concentration**: Top customer is "Euro Shopping Channel" (259 transactions).
- **Geographic Trends**: Most frequent city is "Madrid" and country is "USA."
- **Deal Sizes**: Majority fall into the "Medium" category (1,349 cases).

### Multivariate Analysis

- Examines interactions between multiple variables to identify complex patterns and insights.

### Temporal Analysis

- **Yearly Analysis**: Trends over different years.
- **Monthly Analysis**: Monthly sales patterns and seasonal variations.
- **Weekly Analysis**: Weekly sales trends and patterns.

## Key Insights

- **Sales Trends**: Identified key trends in sales amounts and ordering patterns.
- **Product Performance**: Insights into popular and less popular product lines.
- **Customer Insights**: Understanding top customers and their purchasing behavior.
- **Geographic Insights**: Highlights key regions driving sales.
- **Deal Sizes**: Analysis of predominant deal sizes.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

