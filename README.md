# Business Case Study - E-Commerce Analysis (Brazil)

## 📌 Project Overview

This project involves a comprehensive exploratory data analysis (EDA) of a Brazilian e-commerce dataset. The goal is to derive insights on customer behavior, order trends, logistics efficiency, and payment patterns from 2016 to 2018.

---

## 📂 Dataset Information

* **Source**: SQL tables from the `Project_Target` and `target_sql` databases.
* **Key Tables Used**:

  * `customers`
  * `orders`
  * `payments`
  * `orderitems`

---

## 🔍 Key Analyses Performed

### 1. **Exploratory Data Analysis**

* Checked data types and structure of the `customers` table.
* Identified time span of orders (2016–2018).
* Counted distinct cities and states of customers who placed orders.

### 2. **Order Trends**

* Yearly increase in number of orders (excluding cancellations).
* Monthly seasonality observed: Highest in **August**, **July**, and **May**.
* Most orders placed in the **afternoon**.

### 3. **Geographical Distribution**

* Monthly order trends across Brazilian states.
* Top customer states: **SP**, **RJ**, **MG**.

### 4. **Economic Impact**

* Compared total order payments from Jan–Aug 2017 vs. 2018.
* Identified states with highest average order value and freight costs.

### 5. **Logistics and Delivery**

* Calculated actual delivery time and variance from estimated delivery.
* Identified:

  * Top 5 states with **fastest** and **slowest** delivery.
  * Top 5 states with **lowest** and **highest** average freight.

### 6. **Payment Analysis**

* Order distribution by **payment type** (e.g., credit card, boleto).
* Orders placed on **installments**, with counts by sequential payments.

---

## 📈 Key Insights

* **Growth**: Clear rise in e-commerce orders over the years.
* **Seasonality**: Summer months see a spike in order volume.
* **Customer Behavior**: Afternoon is the most active period for purchases.
* **Logistics**: Faster deliveries and better freight planning improve customer satisfaction.
* **Payments**: Credit card and installment-based payments are widely used.

---

## 📌 Tools & Technologies

* SQL (BigQuery syntax)
* Data visualization via query outputs

---

## 📄 Assumptions

* Only *delivered* orders are considered for delivery-related metrics.
* *Canceled* orders are excluded from most analyses.
* Timezone and timestamp interpretations are based on dataset default (assumed Brazilian timezone).

---

## 👤 Author

* **Sharmeen Khan**
