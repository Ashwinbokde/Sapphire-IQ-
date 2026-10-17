# Amazon Sales Data Analysis

## Project Overview

This project analyses Amazon sales data using Microsoft Excel
PivotTables and charts. The dashboard explores overall sales and
profitability, category performance, yearly profit, order status,
returns and cancellations, payment methods, fulfilment methods, and
state-wise performance.

## Key Business Metrics

-   **Total Sales:** ₹15,57,89,893.89 (approximately ₹15.58 crore)
-   **Total Profit:** ₹3,31,67,008.49 (approximately ₹3.32 crore)
-   **Total Orders:** 10,000
-   **Total Units Sold:** 24,926
-   **Average Order Value:** ₹15,578.99
-   **Profit Margin:** 21.29%

### Interpretation

The business generated approximately ₹15.58 crore in sales and ₹3.32
crore in profit. The average order value was ₹15,578.99, and the profit
margin was 21.29%, meaning the business earned around ₹21.29 in profit
for every ₹100 in sales. The dataset contains 10,000 orders and 24,926
units sold.

> **Note:** Make sure the definitions of sales, profit, and units sold
> are consistent throughout the project. If units sold should exclude
> returned orders, calculate that metric using the relevant order-status
> criteria.

## Objective 2: Sales and Profit Analysis

### Task 1: Category-Wise Sales

  Category                            Total Sales
  ------------------------ ----------------------
  Apparel & Fashion                 ₹98,31,025.09
  Beauty & Personal Care            ₹28,89,178.50
  Electronics & Mobiles           ₹1,23,56,950.71
  Home & Kitchen                  ₹1,79,73,218.93
  Pantry & Groceries                ₹15,26,964.30
  **Grand Total**            **₹15,57,89,893.89**

**Interpretation:** Electronics & Mobiles is the leading category by
sales, followed by Home & Kitchen. Apparel & Fashion contributes a
moderate amount, while Beauty & Personal Care and Pantry & Groceries
contribute less. The company can use this information to understand
which categories generate the most revenue.

### Task 2: Year-Wise Profit

  Year                             Profit
  ----------------- ---------------------
  2024                    ₹1,21,31,109.16
  2025                    ₹1,22,02,423.41
  2026                      ₹88,33,475.92
  **Grand Total**     **₹3,31,67,008.49**

**Interpretation:** Profit remained relatively stable from 2024 to 2025,
increasing slightly in 2025. It then declined in 2026 to approximately
₹88.33 lakh. The company should investigate the reasons for this decline
and look for ways to improve profitability.

### Task 3: Category-Wise Units Sold

  Category                   Units Sold
  ------------------------ ------------
  Apparel & Fashion               6,452
  Beauty & Personal Care          3,734
  Electronics & Mobiles           7,579
  Home & Kitchen                  4,684
  Pantry & Groceries              2,477
  **Grand Total**            **24,926**

**Interpretation:** Electronics & Mobiles has the highest sales volume,
with 7,579 units sold, followed by Apparel & Fashion with 6,452 units.
Pantry & Groceries has the lowest volume, with 2,477 units. These
results can help with inventory planning and understanding customer
demand.

### Task 4: Top 10 Products by Sales

The PivotTable lists the top 10 products by sales. The 5G Smartphone is
among the strongest performers, with sales of approximately ₹2.43 crore.
Laptop Backpack and Power Bank also generate high sales, while products
such as Cotton Bedsheet Double and Induction Cooktop have lower sales in
comparison.

**Interpretation:** The company should monitor stock levels for
high-revenue products and review the performance of lower-revenue
products to identify opportunities for improvement.

## Objective 3: Order Status Analysis

### Order Status Summary

  Order Status        Number of Orders
  ----------------- ------------------
  Cancelled                        500
  Delivered                      8,147
  Returned                         485
  Shipped                          868
  **Grand Total**           **10,000**

**Interpretation:** Most orders were delivered successfully. There were
868 shipped orders, 500 cancelled orders, and 485 returned orders. The
business could investigate the causes of cancellations and returns to
improve customer experience and order fulfilment.

### Return and Cancellation Rates

-   **Return rate:** 5%
-   **Cancellation rate:** 5%

**Interpretation:** Both the return rate and cancellation rate are
approximately 5%. Reviewing product descriptions, delivery issues, order
accuracy, and customer feedback may help reduce these rates.

### Category-Wise Returns and Cancellations

  Category                   Cancelled   Returned     Total
  ------------------------ ----------- ---------- ---------
  Apparel & Fashion                148        110       258
  Beauty & Personal Care            84         75       159
  Electronics & Mobiles            136        164       300
  Home & Kitchen                    91         90       181
  Pantry & Groceries                41         46        87
  **Grand Total**              **500**    **485**   **985**

**Interpretation:** Apparel & Fashion has the highest number of
cancellations (148), while Electronics & Mobiles has the highest number
of returns (164). These categories may need closer review to understand
why customers cancel or return orders.

## Payment Method Analysis

  Payment Method                      Total Sales          Total Profit
  ------------------------ ---------------------- ---------------------
  Amazon Pay Later                  ₹76,84,156.63         ₹16,87,463.99
  Cash on Delivery (COD)          ₹2,31,01,583.64         ₹50,08,107.37
  Credit/Debit Card               ₹3,10,69,230.90         ₹65,25,646.17
  Net Banking                     ₹1,54,19,486.46         ₹32,92,296.82
  UPI                             ₹7,85,15,436.26       ₹1,66,53,494.14
  **Grand Total**            **₹15,57,89,893.89**   **₹3,31,67,008.49**

**Interpretation:** UPI generates the highest sales and profit, making
it the strongest payment method in this dataset. Credit/Debit Cards and
Cash on Delivery are also significant contributors. Amazon Pay Later
contributes the lowest sales and profit among the listed methods.

## Fulfilment Method Analysis

  Fulfilment Method              Total Sales          Total Profit
  ------------------- ---------------------- ---------------------
  Amazon (FBA)              ₹10,75,28,288.07       ₹2,28,82,414.52
  Merchant (FBM)             ₹1,70,63,213.84         ₹34,69,539.45
  Seller Flex                ₹3,11,98,391.98         ₹68,15,054.52
  **Grand Total**       **₹15,57,89,893.89**   **₹3,31,67,008.49**

**Interpretation:** Amazon (FBA) contributes the highest sales and
profit, followed by Seller Flex. Merchant (FBM) has the lowest sales and
profit among the three fulfilment methods. FBA is the leading fulfilment
method in this dataset.

## State-Wise Sales, Profit, and Orders

  ------------------------------------------------------------------------------
  State                     Total Sales          Total Profit        Order Count
  -------------- ---------------------- --------------------- ------------------
  Delhi                 ₹2,23,61,687.04         ₹46,99,095.38              1,444

  Gujarat                 ₹93,69,304.18         ₹20,08,021.80                591

  Karnataka             ₹2,44,15,704.16         ₹52,73,235.35              1,515

  Kerala                  ₹66,11,724.40         ₹13,77,849.56                483

  Maharashtra           ₹2,95,54,237.21         ₹63,01,731.56              1,840

  Rajasthan               ₹66,20,697.25         ₹13,83,028.68                456

  Tamil Nadu            ₹1,78,89,855.25         ₹38,56,864.11              1,109

  Telangana             ₹1,39,61,458.53         ₹29,44,127.16                906

  Uttar Pradesh         ₹1,41,40,675.36         ₹29,78,266.81                991

  West Bengal           ₹1,08,64,550.51         ₹23,44,788.08                665

  **Grand          **₹15,57,89,893.89**   **₹3,31,67,008.49**         **10,000**
  Total**                                                     
  ------------------------------------------------------------------------------

**Interpretation:** Maharashtra has the highest sales (approximately
₹2.96 crore), profit (approximately ₹63.02 lakh), and order count
(1,840). Karnataka and Delhi are also strong-performing states.
Rajasthan has the lowest order count, while Kerala and Rajasthan have
comparatively low sales. The company can use these results to compare
regional performance and identify areas for growth.

## Overall Conclusion

The analysis shows that Electronics & Mobiles is a major contributor to
sales and unit volume, while Maharashtra is the strongest state by
sales, profit, and order count. UPI is the leading payment method, and
Amazon (FBA) is the leading fulfilment method. Most orders were
delivered, but cancellations and returns remain areas to monitor. Profit
also declined in 2026 compared with 2024 and 2025, so further
investigation may help identify ways to improve performance.

## Tools Used

-   Microsoft Excel
-   PivotTables
-   PivotCharts
-   Basic formulas and summary metrics

## Suggested Future Improvements

-   Analyse monthly and quarterly sales trends.
-   Compare profit margins by category, product, state, and payment
    method.
-   Investigate reasons for cancellations and returns.
-   Check whether returned orders should be excluded from units sold and
    revenue metrics.
-   Add slicers and a dashboard for interactive filtering.
