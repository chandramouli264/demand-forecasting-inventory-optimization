# Demand Forecasting and Inventory Optimization Using Machine Learning

## Week 1: Data Collection, Quality Checks and Exploratory Data Analysis

### Objective
Collect and inspect the M5 Forecasting dataset, validate its quality, and explore initial sales patterns.

### Dataset
Source: [Kaggle M5 Forecasting Accuracy](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data)

Files used:
- `sales_train_validation.csv`
- `calendar.csv`
- `sell_prices.csv`

### Work Completed
- Loaded and inspected the three datasets.
- Checked missing values and duplicate records.
- Validated daily sales columns and calendar date mappings.
- Checked product-store consistency and price coverage.
- Examined zero-sales observations.
- Created plots for daily sales trends, category sales, and zero-sales-day distribution.
- Documented the data dictionary, quality checks, source, and limitations.

### Key Findings
- 3,049 products across 10 stores.
- No missing daily sales values or duplicate keys were identified in the checks performed.
- FOODS has the highest total sales among the three categories.
- Many product-store series contain numerous zero-sales days.
- Approximately 21.03% of derived product-store-week combinations have no matching price record.

### Limitations
The selected datasets do not provide complete inventory-on-hand quantities, explicit stockout records, or supplier lead times. Zero sales cannot automatically be interpreted as lost demand or a stockout.

### Week 1 Status
Data collection, data-quality checks, and initial EDA are completed. Forecasting and inventory optimization will be addressed in later project stages.