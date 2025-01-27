# Customer Segmentation and Business Insights

This repository contains the solution to a customer segmentation task using K-Means clustering on an eCommerce transactions dataset. The analysis was performed to segment customers based on their transaction behavior and profile characteristics. This project includes **Exploratory Data Analysis (EDA)**, **Clustering** (K-Means), and **Business Insights** derived from the segmentation.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Installation](#installation)
- [Task 1: Exploratory Data Analysis (EDA)](#task-1-exploratory-data-analysis-eda)
- [Task 2: Lookalike Model](#task-2-lookalike-model)
- [Task 3: Customer Segmentation and Clustering](#task-3-customer-segmentation-and-clustering)
- [Evaluation Metrics](#evaluation-metrics)
- [Recommendations](#recommendations)
- [Usage](#usage)
- [License](#license)

## Project Overview

This project aims to segment customers using the provided eCommerce dataset, which includes customer profiles, transaction history, and product data. We used **K-Means clustering** to form customer segments and derived actionable business insights from the analysis. The report also includes a summary of the clustering results, business insights, and recommendations for targeted marketing strategies.

### Task Breakdown

1. **Task 1: Exploratory Data Analysis (EDA)**
   - Conducted initial data exploration to understand key features and identify patterns in customer behavior, spending, and product preferences.

2. **Task 2: Lookalike Model**
   - Built a model to recommend similar customers based on their profiles and transaction history. This model calculates similarity scores and recommends top 3 similar customers for each given customer.

3. **Task 3: Customer Segmentation / Clustering**
   - Performed customer segmentation using **K-Means clustering** on both customer profile and transaction data. The segmentation resulted in **4 clusters** based on transaction behavior, spending patterns, and frequency of purchases.

## Data Description

The dataset consists of three CSV files:

1. **Customers.csv**
   - CustomerID: Unique identifier for each customer.
   - CustomerName: Name of the customer.
   - Region: Continent where the customer resides.
   - SignupDate: Date when the customer signed up.

2. **Products.csv**
   - ProductID: Unique identifier for each product.
   - ProductName: Name of the product.
   - Category: Product category.
   - Price: Product price in USD.

3. **Transactions.csv**
   - TransactionID: Unique identifier for each transaction.
   - CustomerID: ID of the customer who made the transaction.
   - ProductID: ID of the product sold.
   - TransactionDate: Date of the transaction.
   - Quantity: Quantity of the product purchased.
   - TotalValue: Total value of the transaction.
   - Price: Price of the product sold.

## Installation

To run the code and reproduce the analysis, clone this repository and install the required dependencies:

```bash
git clone https://github.com/sollitudedinesh/dineshkumar_s_assignment.git
cd dineshkumar_s_assignment
