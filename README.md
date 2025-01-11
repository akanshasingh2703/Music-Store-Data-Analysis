# **Music Store Data Analysis**

## **Project Overview**
This project focuses on analyzing the data of a digital music store using SQL. The objective is to answer a series of business-driven questions related to customers, invoices, artists, genres, and tracks. By writing efficient SQL queries, insights are derived that can help improve customer engagement, identify top-performing artists, and optimize the music store's offerings.

The queries are organized into three difficulty levels: **Easy**, **Moderate**, and **Advanced**, with each level addressing progressively complex business questions.

---

## **Data Source**
The dataset consists of multiple tables representing a music store's business data. Key tables include:
- **Customer**: Information about customers, including their name, email, and billing country.
- **Invoice**: Details of invoices, including totals, billing cities, and countries.
- **Invoice_Line**: Line items of invoices, including track purchases.
- **Track**: Metadata about tracks, such as names, genres, and durations.
- **Genre**: Different music genres available in the store.
- **Album**: Information about albums associated with tracks.
- **Artist**: Information about artists contributing to the albums.

---

## **Objectives**
The project addresses key business questions divided into three sets:

### **Question Set 1: Easy**
1. Identify the **senior-most employee** based on job title.
2. Find **countries** with the most invoices.
3. Retrieve the **top 3 invoice totals**.
4. Identify the **city generating the highest revenue**.
5. Determine the **best customer** based on spending.

### **Question Set 2: Moderate**
1. Retrieve the email, first name, and last name of all **Rock music listeners**.
2. Identify the **top 10 artists** with the most Rock tracks in the dataset.
3. Find tracks with a duration **longer than the average song length**, and list them in descending order.

### **Question Set 3: Advanced**
1. Calculate how much **each customer spent on artists** and identify the most popular artists.
2. Determine the **most popular music genre in each country** based on the number of purchases.
3. Identify the **top customer in each country** by spending and handle ties if the highest amount is shared.

---

## **Key Features**
- **Business-Driven Insights**: The queries focus on practical business questions such as customer preferences, top-performing cities, and the popularity of artists and genres.
- **SQL Techniques Used**:
  - Aggregations (`SUM`, `COUNT`, `AVG`)
  - Joins (`INNER JOIN`, `LEFT JOIN`)
  - Subqueries and Common Table Expressions (CTEs)
  - Sorting and Filtering (`ORDER BY`, `WHERE`, `GROUP BY`)
  - Window Functions (`ROW_NUMBER()`, `PARTITION BY`)
  - Recursive CTEs for advanced queries
- **Efficient Query Design**: Queries are optimized to handle grouped data, nested queries, and ranking efficiently.

