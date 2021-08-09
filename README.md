# Sales forecasting for wholesale copmpay with ARIMA model

Using sales data from Wholesale company build a model to predict sales for next 6 months using ARIMA model

## Table of contents
* [Task Description](#task-description)
* [Quickstart](#quickstart)
* [Technologies](#technologies)
* [Sources](#sources)


## Task Description

In Sales_data.csv file provided information on sales of Wholesale company for YY2014-10MYY2017. Data includes sales, units and stock on level SKU, Retailer, Date.

Columns’ description:

- 'Date': week of sales
- 'Sales" : sales amount
- 'Units': count of sold units
- 'Stock': count of units in stock
- 'Retailer': retailer identifier
- 'SKU': SKU (stock keeping unit) identifier

Based on provided data make predictions for next 6M sales for the company using ARIMAX model.

## Quickstart

A virualenv is recommended to use working withing Anaconda environment:

```bash
conda create -n my-env
conda activate my-env
```

Activate your virtual environment and install packages:
```bash
conda activate my-env
```

And run the notebooks with (all packages run in Anaconda out of the box):

```bash
jupyter notebook
```

Then you can follow the notebook interactively by running file (to predict sales for the company for next 6 months):

ARIMA_model_forecast.ipynb

Or Then you can build forecast for specific product by running file:

ARIMA_model_forecast_by_SKU.ipynb

## Technologies
Jupyter Notebook: 6.4.0
Libraries:
    - Numpy: 1.20.3
    - Pandas: 1.3.0
    - Matplotlib: 3.3.4
    - Statsmodels: 0.12.2

## Sources
The provided data file do not have any commercial information