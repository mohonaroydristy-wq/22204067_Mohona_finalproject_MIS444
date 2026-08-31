# MIS444 Retail Sales Predictive Analytics

## Project
Regression-based predictive analytics for estimating `Total Amount` in the supplied retail sales dataset.

## Files
- `MIS444_Retail_Sales_Predictive_Analytics.ipynb` — Google Colab-ready notebook
- `retail_sales_dataset.csv` — dataset
- `MIS444_Retail_Sales_Project_Report.docx` — project report

## Models
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. GridSearchCV optimization for Random Forest

## Important methodological note
In this dataset, `Total Amount` is determined by `Quantity × Price per Unit`. Therefore, tree-based models can achieve essentially perfect performance. This should be treated as a dataset limitation and discussed in the report, not as evidence of general future-sales forecasting ability.

## Colab
Upload the `.ipynb` file to Google Colab, then upload `retail_sales_dataset.csv` when the first cell asks for it. Run all cells from top to bottom.
