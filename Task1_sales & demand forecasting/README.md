# Sales & Demand Forecasting Using Linear Regression

---

## Project Overview

---

This project focuses on predicting future sales using Machine Learning techniques. Historical supermarket sales data is analyzed, cleaned, and processed to build a Linear Regression model capable of forecasting future sales trends.

The project uses sales records containing order dates and total sales values. After preprocessing the data and converting date information into a machine-readable format, a Linear Regression model is trained to predict future sales for the next 30 days.

---

## Features

---

* Load and preprocess supermarket sales data
* Convert date information into a time-series format
* Train a Linear Regression model
* Forecast future sales trends
* Visualize actual and predicted sales
* Generate sales forecasting graphs
* Predict sales for future dates

---

## Dataset

---

The dataset contains supermarket sales records with important fields such as:

| Column Name        | Description                   |
| ------------------ | ----------------------------- |
| Order Date         | Date of the sales transaction |
| Total (USD)        | Total sales amount generated  |
| Order Quantity     | Number of items ordered       |
| Retail Price (USD) | Price per item                |

### Example

| Order Date | Total (USD) |
| ---------- | ----------- |
| 01/01/2024 | 500.25      |
| 01/02/2024 | 720.40      |
| 01/03/2024 | 610.75      |

---

## Technologies Used

---

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* OpenPyXL

---

## Machine Learning Algorithm

---

### Linear Regression

Linear Regression is used to identify the relationship between time and sales values. The model learns historical sales patterns and predicts future sales trends based on previously observed data.

---

## Installation

---

```bash
git clone <repository-url>
cd FUTURE_ML_01
```

```bash
pip install -r requirements.txt
```

---

## Usage

---

1. Place the dataset file (`Supermarket-Sales-Sample-Data.xlsx`) in the project directory.
2. Open the notebook:

```bash
jupyter notebook Sales_Demand_Forecasting.ipynb
```

3. Execute all cells sequentially.
4. View the generated forecasts and graphs.

---

## Output

---

The project generates:

* Future sales predictions for the next 30 days
* Sales trend visualization
* Forecasted sales graph
* Actual vs Predicted sales comparison

---

## Project Structure

---

```text
FUTURE_ML_01/
│
├── dataset/
│   └── Supermarket-Sales-Sample-Data.xlsx
│
├── images/
│   └── sales_trend.png
│
├── Sales_Demand_Forecasting.ipynb
├── README.md
├── requirements.txt
└── report.pdf
```

---

## Future Enhancements

---

* Support advanced forecasting algorithms
* Improve prediction accuracy using Random Forest and XGBoost
* Interactive dashboard using Streamlit
* Automated model evaluation metrics
* Real-time sales forecasting

---

## Conclusion

---

This project demonstrates how Machine Learning can be used to forecast future sales using historical business data. Accurate sales forecasting helps businesses optimize inventory management, improve decision-making, and enhance operational efficiency.

---

## Author

---

**RithvikRaj Karakambadi**
