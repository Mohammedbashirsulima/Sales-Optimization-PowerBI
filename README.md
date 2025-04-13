# 🚀 Power BI Project: Adventure Works Sales Optimization

This project was built as part of the final course in Microsoft's Data Analyst Certification (PL-300). It demonstrates advanced Power BI skills such as data modeling, DAX usage, and model optimization using the AdventureWorks dataset.

---

## 📘 Scenario

Adventure Works is experiencing stagnant sales and increasing inventory problems. This report analyzes sales, customer, and order data to deliver actionable insights that support better decision-making and business alignment.

---

## 🧱 Data Model Overview

**Tables Included:**
- `Customers`
- `Orders`

**Relationship:**
- `Customer ID`: One-to-Many from Customers to Orders (Single cross-filter direction)

**Data Types Optimization:**

**Customers Table:**
- Name → Text  
- Surname → Text  
- Location → Text  
- Date of Birth → Date  
- Phone Number → Text  
- Membership Tier → Text  
- Customer Source → Text  

**Orders Table:**
- Order Total → Decimal number  
- Order ID → Whole Number  
- Customer ID → Whole Number  
- Product ID → Whole Number  
- Order Date → Date  
- Order Status → Text  
- Order Quantity → Whole Number  
- Payment Method → Text  
- Billing Address → Text  
- Discounts → Decimal number  
- Shipping Fee → Decimal number  
- Tracking Number → Text  

---

## ⚙️ Optimization Techniques

- ✅ **Auto date/time disabled** from Power BI Options to improve model performance  
- ✅ All data types verified and set manually  
- ✅ Relationship manually configured for clarity and accuracy


## 📌 Author

**Mohamed-Bashir-Suliman**  
Data Analyst  



