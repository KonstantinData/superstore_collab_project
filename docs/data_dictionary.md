# **Superstore Dataset – Data Dictionary**

This document provides an overview of the columns in the **Superstore dataset**, including descriptions, data types, and key details.

## **📌 Column Descriptions**

| Column Name  | Data Type | Description |
|-------------|------------|-------------|
| **Row ID**  | int64      | Unique identifier for each row in the dataset. |
| **Order ID**  | object    | Unique identifier for each order. Multiple rows may share the same Order ID if an order contains multiple products. |
| **Order Date**  | object  | The date when the order was placed. |
| **Ship Date**  | object  | The date when the order was shipped. |
| **Ship Mode**  | object  | The shipping method used (e.g., Standard Class, First Class, Second Class, Same Day). |
| **Customer ID**  | object  | Unique identifier for each customer. |
| **Customer Name**  | object  | Full name of the customer. |
| **Segment**  | object  | Customer segment (e.g., Consumer, Corporate, Home Office). |
| **Country**  | object  | Country where the order was placed. |
| **City**  | object  | City where the order was placed. |
| **State**  | object  | State where the order was placed. |
| **Postal Code**  | object  | Postal code of the shipping address. |
| **Region**  | object  | Region classification (e.g., West, East, Central, South). |
| **Product ID**  | object  | Unique identifier for each product. |
| **Category**  | object  | Product category (e.g., Office Supplies, Furniture, Technology). |
| **Sub-Category**  | object  | More specific classification within a category (e.g., Binders, Chairs, Phones). |
| **Product Name**  | object  | Name of the product. |
| **Sales**  | float64  | Total sales amount for the product in the order. |
| **Quantity**  | int64  | Number of units sold for the order. |
| **Discount**  | float64  | Discount applied to the order. |
| **Profit**  | float64  | Profit earned from the order. |

## **📌 Notes**
- The dataset contains **9994 rows**.
- Order and shipping dates may be used for **time series analysis** or calculating **order processing time**.
- Ship Mode, Segment, Category, and Region are **categorical variables**.
- Sales, Quantity, Discount, and Profit are **numerical variables** and useful for **financial analysis**.

This dictionary will be updated as we explore more columns! 🚀

