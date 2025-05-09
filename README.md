# Discount Analysis on Conversion Rate ( Furniture )
This project explores how **discount rates** influence **conversion rates**, with additional insights by product category.

---

## 📌 Objectives

1. Analyze the impact of discount rate on conversion rate.
2. Determine if a higher discount leads to better conversion.
3. Examine trends across product categories.
4. Provide actionable business recommendations.

---

## 📈 Key Findings

- There is a **positive but nonlinear** relationship between discount rate and conversion rate.
- After removing extreme outliers, **conversion rates tend to improve** in the moderate discount range of **20–35%**.
- Extremely **low or high discounts do not guarantee better conversions**.
- **Product categories respond differently** to discounts. For example, `Storage` and `Accessories` see higher responsiveness.
- **Cleaning outliers** helps avoid misleading results and improves decision-making.

---

## 💡 Business Implications

- Use moderate discounts (20–35%) to boost conversions effectively.
- Avoid overly high discounts that may waste marketing budget.
- Tailor discount strategies for each product category.
- Clean data for more accurate insights.

---

## 📊 Data Dictionary

| Column name           | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `market`              | Market where the product is sold                                            |
| `region`              | Market broken down into regions                                             |
| `date`                | Date when the product is sold                                               |
| `skuid`               | The unique ID of a product                                                  |
| `curleadtime`         | Days before a product can be shipped to the customer (0 = immediate ship)   |
| `original_price`      | Original price of the product                                               |
| `actual_sale_price`   | Selling price of the product on the given date and region                   |
| `daily_quantity_sold` | Quantity sold of the product on the given date and region                   |
| `perfcat`             | Product performance class (bestseller → medium → slow)                      |
| `category`            | Product category                                                            |

---

## 📂 File Structure

- `notebook/furniture.ipynb`: Main Jupyter Notebook with data cleaning, visualization, and insights.
- `presentation/`: Slides summarizing findings.
- `data/`: Processed data used for analysis and plotting.





