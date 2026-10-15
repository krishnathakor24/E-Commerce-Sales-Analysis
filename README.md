# Madhav E-Commerce Sales Dashboard (Power BI)

A single-page, interactive Power BI dashboard that summarizes e-commerce sales performance: revenue, profit, quantity sold, and average order value, broken down by time, product, payment mode, state, and customer.

<img width="640" height="357" alt="image" src="https://github.com/user-attachments/assets/44cd1b70-0e90-4da3-90eb-87fb4a8ce370" />

## Objective
Give a sales manager a one-page view of business health and let them drill into where profit comes from, which products and regions perform, and how customers pay.

## Data Model
The report is built on two related tables:

| Table | Contents |
|---|---|
| **Orders** | Order-level information: order date (with a date hierarchy), state, customer name |
| **Details** | Line-level information: category, sub-category, quantity, amount, profit, payment mode |

Measures used: total **Amount** (sales), total **Profit**, total **Quantity**, and **AOV** (average order value).

## Dashboard Contents
**KPI cards**
- Total sales (Amount)
- Total profit
- Total quantity sold
- Average order value (AOV)

**Charts**
| Visual | Purpose |
|---|---|
| Profit by Month (column) | Seasonality and profit trend |
| Profit by Sub-Category (bar) | Which product lines earn the most |
| Quantity by Category (donut) | Product category mix by units |
| Quantity by Payment Mode (donut) | How customers prefer to pay |
| Top States (bar) | Regional sales performance |
| Sales by Customer (column) | Highest-value customers |

## Interactivity
- **Quarter slicer** to focus on a period
- **State slicer** to filter the whole page to one region
- Cross-filtering: selecting any chart element updates the other visuals

## Questions It Answers
- Which months and sub-categories drive the most profit?
- Which categories sell the most units?
- Which payment modes are most popular?
- Which states and customers contribute the most sales?
- How do sales, profit, and AOV change by quarter or state?

## Author
Krishna Thakor · [LinkedIn](https://www.linkedin.com/in/krishnamaheshchandrathakor/) · [Email](mailto:krishnathakor2411@gmail.com)
