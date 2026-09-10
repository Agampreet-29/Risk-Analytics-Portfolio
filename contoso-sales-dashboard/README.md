# Contoso Global Sales Dashboard

## What it does

An interactive HTML sales dashboard built on the Contoso global electronics retailer dataset — a multi-table relational dataset covering customers, products, stores, sales transactions, and currency exchange rates across multiple countries.

## Dataset

Five linked tables (see `Data_Dictionary.csv` for the full field-level breakdown):
- **Sales.csv** — order-level transactions (order number, dates, customer/store/product keys, quantity, currency)
- **Customers.csv** — customer demographics and location
- **Products.csv** — product catalog with cost, price, category, and subcategory
- **Stores.csv** — store locations, size, and open dates
- **Exchange_Rates.csv** — daily currency exchange rates vs. USD, used to normalize sales across currencies

## How it was built

Originally built as a Power BI model (data relationships across the five tables via keys), then reconstructed as a standalone interactive HTML dashboard so it's viewable without a Power BI license.

## How to view it

Open `contoso_sales_dashboard_.html` directly in any browser — no installation required. The raw CSVs are included for anyone who wants to see or re-model the underlying data.

## Skills demonstrated

Data Modeling · Microsoft Power BI · SQL-style relational thinking (keys across tables) · Data Visualization
