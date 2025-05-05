# Practical Application 1: Will the Customer Accept the Coupon?

## Overview
This project analyzes survey data to explore whether a customer will accept a driving-related coupon. Using Python and visualization tools, we identify trends and differences between customers who accepted the coupon (`Y = 1`) and those who did not (`Y = 0`).

## Data Source
The dataset is from the UCI Machine Learning Repository and was collected via Amazon Mechanical Turk. It includes:
- Driving scenarios
- Weather, destination, time, passenger info
- Customer response: Accept or reject coupon

## Methodology
- Cleaned and explored the dataset using `pandas`
- Created summary statistics to understand key differences
- Visualized patterns using `matplotlib` and `seaborn`

## Key Insights
- Customers are more likely to accept coupons for cheaper restaurants and coffee houses
- Time of day and weather conditions influence coupon acceptance
- Solo passengers tend to reject coupons more than groups

## Recommendations
- Target coupons during favorable conditions (e.g., clear weather, group trips)
- Emphasize urgency (e.g., “expires soon”) to increase acceptance

## Files Included
- `Coupon_Acceptance_Analysis.ipynb`: Main analysis notebook
- `README.md`: This summary file

## Tools Used
- Python 3
- pandas
- matplotlib
- seaborn
