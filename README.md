# Supply-Chain-Analytics-Project
This project focuses on predicting future product demand, a process known as demand forecasting, which helps businesses anticipate customer needs.


## Project Objective

This project focuses on predicting future product demand, a process known as demand forecasting, which helps businesses anticipate customer needs.

## Overview of Dataset

- **Origin:** UCI Machine Learning Repository ([Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail))
- **Nature of Data:** Time-Series, Multivariate, and Sequential
- The dataset comprises transactions from a UK-based online store, spanning 2010–2011. The business specializes in unique gifts and caters to many wholesale customers.
- **Key Columns:**
  - `InvoiceNo`
  - `StockCode`
  - `Description`
  - `Quantity`
  - `InvoiceDate`
  - `UnitPrice`
  - `CustomerID`
  - `Country`

## Feature Development

- **Text Feature Extraction:**
  - A new column, `Product_type`, was created by identifying nouns from product descriptions.
  - Product colors were isolated from descriptions
