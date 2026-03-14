# MSCS_634_Lab_1

## Purpose
This lab demonstrates how to use Jupyter Notebook for data collection, data visualization, preprocessing, and statistical analysis. A retail sales dataset was used to show how raw data can be explored, cleaned, reduced, scaled, and analyzed.

## Files Included
- `MSCS_634_Lab_1.ipynb` - Completed Jupyter Notebook
- `retail_sales_data.csv` - Dataset used in the lab
- `screenshots/` - Required screenshots for outputs and visualizations
- `README.md` - Summary of the lab work

## Key Insights
- Average monthly revenue stayed relatively stable across the period, with January showing the highest monthly average and May showing the lowest.
- Electronics produced the highest average revenue, while Office Supplies produced the lowest.
- Missing values were successfully handled using median replacement for numeric fields and mode replacement for the categorical field.
- One revenue outlier was identified and removed using the IQR method.
- Correlation analysis showed that `Unit_Price` had the strongest positive relationship with `Revenue`, while `Discount_Percent` had a small negative relationship with `Revenue`.

## Challenges and Decisions
- A compact retail sales dataset was used so the notebook could clearly demonstrate missing values, outliers, preprocessing, and statistical analysis in one place.
- Median imputation was selected for numeric missing values because it is less sensitive to extreme values than the mean.
- Min-Max scaling was applied to revenue and marketing spend to place them on a comparable scale.
- Customer ratings were discretized into labeled categories to make interpretation easier.

## GitHub Submission
Create a public GitHub repository named `MSCS_634_Lab_1`, upload all files from this folder, and submit the repository link to the instructor.
