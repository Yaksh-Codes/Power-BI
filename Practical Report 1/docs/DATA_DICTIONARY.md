# 📚 Data Dictionary

**File:** `data/Superstore_Sales_Dataset.csv` — 51,325 rows × 21 columns (2011–2014)

| Column | Type | Description |
|---|---|---|
| order_id | Text | Unique order identifier |
| order_date | Date | Date the order was placed |
| ship_date | Date | Date the order was shipped |
| ship_mode | Text | Standard Class, Second Class, First Class, Same Day |
| customer_name | Text | Customer full name |
| segment | Text | Consumer, Corporate, Home Office |
| state | Text | State / province of delivery |
| country | Text | Country of delivery (147 countries) |
| market | Text | Africa, APAC, Canada, EMEA, EU, LATAM, US |
| region | Text | Sales region (13 regions) |
| product_id | Text | Unique product identifier |
| category | Text | Furniture, Office Supplies, Technology |
| sub_category | Text | 17 sub-categories (e.g. Chairs, Phones, Tables) |
| product_name | Text | Product name |
| sales | Number | Sales amount in USD |
| quantity | Integer | Units sold |
| discount | Decimal | Discount applied (0 to 1) |
| profit | Decimal | Profit in USD (can be negative) |
| shipping_cost | Decimal | Cost to ship the order |
| order_priority | Text | Low, Medium, High, Critical |
| year | Integer | Order year |
