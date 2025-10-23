# predict-visualize-automate
End-to-end BI workflow using Python, Tableau &amp; automation (Predict → Visualize → Automate)
# Predict → Visualize → Automate

An end-to-end Business Intelligence project demonstrating how to predict sales using Python, visualize results in Tableau and prepare an automated dashboard refresh.

## Project structure
- `data/` - raw and generated datasets (`sales_forecast_dataset.csv`, `forecasted_sales.csv`, `sales_for_tableau.csv`)
- `notebooks/` - Jupyter notebook showing data cleaning and forecasting (`01_sales_forecast.ipynb`)
- `tableau_dashboard/` - exported Tableau workbook (optional)
- `images/` - dashboard screenshots

## How to run
1. Download or clone this repo.
2. Open `notebooks/01_sales_forecast.ipynb` in Jupyter (or VS Code).
3. Ensure `data/sales_forecast_dataset.csv` is in the `data/` folder relative to the notebook.
4. Run the cells to generate `data/forecasted_sales.csv` and `data/sales_for_tableau.csv`.
5. Open `sales_for_tableau.csv` in Tableau to reproduce dashboards.

## Tools
- Python (pandas, scikit-learn, matplotlib)
- Tableau Desktop / Tableau Public
- (Optional) Tableau Server for automation

## Contact
Vidit Nanu — BI Analyst  
LinkedIn: https://linkedin.com/in/viditnanu
