# AdventureWorks Sales Analysis

## Introduction

Welcome to the AdventureWorks Sales Analysis project! This repository contains SQL queries designed to identify the best products and salespeople.

### Business Context

AdventureWorks is an outdoor sporting equipment retailer with multiple locations. As a data analyst, the task is to extract meaningful insights from sales data to boost sales figures.

### Analytical Approach

The initial plan includes:

- Loading the SQLite database and running basic queries.
- Examining relationships between product ratings and total sales.
- Analyzing product performance across different subcategories.
- Identifying top-performing salespeople in 2014.
- Investigating correlations between total sales and commission percentage.

_Note: The approach may evolve during database exploration._

## Data Preparation

The analysis focuses on 'Sales' and 'Product' category tables within `AdventureWorks.db`.

### Key Tables Overview

**Product Table:**

- `Product`: Details of each product sold by the company.
- `ProductReview`: Customer ratings and reviews.
- `ProductModelProductDescriptionCulture`: Links products with descriptions in various languages/regions.
- `ProductDescription`: Longer descriptions of each product for specific regions.
- `ProductCategory`: Broad categories that products fit into.
- `ProductSubCategory`: Narrower subcategories that products fit into.

**Sales Table:**

- `SalesPerson`: Data on each salesperson's commission rate and performance metrics.
- `SalesOrderHeader` & `SalesOrderDetail`: Summarized details of individual sales transactions.
- `SalesTerritory`: Performance data for different sales territories.
- `CountryRegionCurrency`: Currency used by each region.
- `CurrencyRate`: Average and closing exchange rates for each currency compared to USD.

## Recommendation

One recommendation to increase sales is to have the top salesperson per currency code (SalesPersonID: 286, 289, 288, 282, and 276) focus on selling the most purchased items such as logo caps, helmets, jerseys, and water bottles.

---

_This README serves as a guide for navigating through the analysis process within this repository._
