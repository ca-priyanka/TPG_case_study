# Data Analysis Assignment: Customer Churn Analysis in SQL

## Overview

This repository contains SQL scripts and queries for analyzing customer churn in a telecommunications company. The goal is to identify patterns and factors contributing to customer churn based on the provided dataset.

## Dataset

The dataset includes relevant information about customers, their usage, and churn status. The key columns include `customer_id`, `losing_nbn_speed`, `gaining_nbn_speed`, and `churn_date`. The `churn_date` column indicates the date when a customer churned.

## Analysis Steps

1. **Exploratory Data Analysis (EDA):**
   - Understand the dataset structure and contents.
   - Identify missing values, outliers, and any data quality issues.
   - Generate summary statistics for key metrics.

2. **Data Preprocessing:**
   - Handle missing values and outliers appropriately.
   - Ensure data types are consistent.
   - Transform and clean data for analysis.

3. **Feature Engineering:**
   - Derive relevant features that may contribute to churn analysis.
   - Explore relationships between variables.

4. **Churn Analysis:**
   - Utilize SQL queries to identify patterns related to customer churn.
   - Investigate the distribution of churn across different customer segments.
   - Analyze the impact of factors such as speed changes on churn.

5. **Visualization (Optional):**
   - Create visualizations to present key findings.
   - Use charts or graphs to enhance understanding.

6. **Conclusion and Recommendations:**
   - Summarize key insights and observations.
   - Provide recommendations for reducing churn based on the analysis.

## Usage

1. **Database Setup:**
   - Ensure you have a MySQL database set up.
   - Import the dataset into your database.

2. **Run SQL Scripts:**
   - Execute the SQL scripts in the specified order to perform the analysis.

3. **Review Results:**
   - Examine the results of each query to understand the churn analysis outcomes.

## Files

- **`exploratory_analysis.sql`:** Perform exploratory data analysis on the dataset.
- **`data_preprocessing.sql`:** Preprocess the data to handle missing values and outliers.
- **`feature_engineering.sql`:** Create additional features for churn analysis.
- **`churn_analysis.sql`:** Conduct customer churn analysis using SQL queries.
- **`visualization.sql` (Optional):** Generate visualizations based on analysis results.

## Dependencies

- MySQL database
- Dataset: [Link to Dataset]

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The dataset used in this analysis is provided by [Source].

Feel free to customize this README to include specific details about your dataset, analysis methods, and any additional information relevant to your assignment.
