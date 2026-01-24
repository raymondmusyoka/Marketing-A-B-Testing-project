A/B Testing Analysis for Digital Marketing Campaigns
Project Overview

This project evaluates the effectiveness of marketing campaign variations using A/B testing. The goal is to determine which campaign variant drives higher engagement and conversion, and to provide actionable recommendations for marketing teams.

Business Problem

Marketing teams often run multiple campaigns without clear insight into which version performs best. This project quantifies the impact of different campaign variations on user behavior and conversions, enabling data-driven decisions.

Dataset

Sourced from a messy GitHub marketing dataset ([link to CSV])

User-level campaign data including:

user_id

group (control vs variant)

Engagement metrics (clicks, views)

Conversion indicator

Demographics (age, gender, location)

Dataset required cleaning due to missing values, inconsistent labels, and mixed data types.

Methodology

Data Cleaning and Preprocessing

Standardized group labels and corrected data types

Handled missing or duplicate records

Validated sample sizes and metric distributions

Metric Definition

Primary: Conversion rate

Secondary: Click-through rate, revenue per user

Guardrail: Bounce rate, session duration

Experiment Design

Control vs variant groups

Random assignment simulated

Duration: based on dataset sample size

Statistical Analysis

Two-sample t-tests for conversion rate differences

Chi-square tests for categorical metrics

Calculated p-values and confidence intervals

Visualization

Comparative charts of conversion rates

Lift charts and metric summaries

Key Skills Demonstrated

Data cleaning and preprocessing

SQL for data extraction and aggregation

Python for statistical analysis and visualization

Hypothesis testing and experimental evaluation

Translating data insights into business recommendations

Results

Identified the campaign variant with a statistically significant increase in conversion

Quantified the lift in engagement metrics and conversion rate

Provided recommendations to optimize future marketing campaigns

Tools Used

Python: pandas, numpy, scipy, matplotlib, seaborn

SQL

Jupyter Notebook

Conclusion

This project demonstrates an end-to-end A/B testing workflow for marketing campaigns, from messy data cleaning to actionable business insights. It highlights how data analytics can guide marketing strategy and improve campaign effectiveness.
