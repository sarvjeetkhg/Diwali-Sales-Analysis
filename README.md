# Diwali-Sales-Analysis
A complete EDA project analyzing Diwali sales trends and customer insights using Python, Pandas, Matplotlib, and Seaborn.

## Project Overview

This project performs exploratory data analysis (EDA) on a Diwali sales dataset to uncover trends, insights, and actionable recommendations. The analysis is implemented in the Jupyter notebook `Diwali_Sales_Analysis.ipynb` and includes data cleaning, feature engineering, visualizations, and a short summary of findings.

**Key goals**

* Clean and prepare the dataset for analysis
* Visualize sales patterns over time and across product categories
* Identify top-performing products, regions, and months
* Provide business recommendations backed by data

---

## Files in this repository

* `Diwali_Sales_Analysis.ipynb` — Main Jupyter notebook with EDA, charts and conclusions.
* `data/` — (optional) folder where the raw CSV/Excel files used by the notebook should be stored.
* `README.md` — This file.
* `requirements.txt` — (optional) Python dependencies for reproducing the analysis.

> If your repository contains additional scripts, models, or exported charts, list them here.

---

## ## Dataset

* **Rows:** 11251
* **Columns:** 15
* **Column Names:**

  * User_ID, Cust_name, Product_ID, Gender, Age Group, Age, Marital_Status, State, Zone, Occupation, Product_Category, Orders, Amount, Status, unnamed1

*(Dataset automatically extracted from the uploaded CSV file.)*

Briefly document where the dataset comes from and its structure. Example:

* Source: `data/diwali_sales.csv` (replace with your actual filename)
* Typical columns: `OrderID`, `OrderDate`, `Product`, `Category`, `Quantity`, `Price`, `City`, `State`, `Revenue`
* Rows: N (replace with actual row count)

If the data is private or contains sensitive fields, note that here and explain any anonymization steps you took.

---

## Requirements (Python environment)

Create a virtual environment and install the dependencies. Example using `venv`:

```bash
python -m venv venv
source venv/bin/activate    # macOS / Linux
venv\Scripts\activate     # Windows (PowerShell)
pip install -r requirements.txt
```

Example `requirements.txt` - add this to the repository if you want reproducibility:

```
pandas
numpy
matplotlib
seaborn
jupyterlab
plotly
openpyxl
```

---

## How to run the notebook (locally)

1. Clone the repo:

```bash
git clone https://github.com/sarvjeetkhg/diwali-sales-analysis.git
cd diwali-sales-analysis
```

2. Ensure the data files are in `data/` or update the notebook data paths.
3. Start JupyterLab / Jupyter Notebook:

```bash
jupyter lab
# or
jupyter notebook
```

4. Open `Diwali_Sales_Analysis.ipynb` and run cells sequentially. The notebook includes comments that explain each step.

---

## Key outputs and visualizations

Summarize what the notebook produces (so a reader knows what to look for):

* Data quality summary (missing values, duplicates)
* Revenue by month / seasonality charts
* Top products and categories by revenue
* Sales heatmap by city/state
* Recommendations and next steps

You can export the notebook as HTML or PDF for sharing:

```bash
jupyter nbconvert --to html Diwali_Sales_Analysis.ipynb
jupyter nbconvert --to pdf Diwali_Sales_Analysis.ipynb
```

---

## Findings & Recommendations (example)

* Highest revenue occurs during October–November — align inventory and marketing accordingly.
* Top categories: `X`, `Y` — focus promotional offers on these.
* Cities `A`, `B` show strong repeat purchases — consider localized campaigns.

(Replace the example bullets with your actual findings.)

---
## Contact

Sarvjeet Kumar — 
LinkedIn: [https://www.linkedin.com/in/sarvjeetkhg](https://www.linkedin.com/in/sarvjeetkhg)

---
