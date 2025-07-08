# 📁 Data Folder

This folder contains the raw dataset files used in building the **Electro Hub - Retail Sales Dashboard**.

## Files Included

- **ElectroHub_RawData.xlsx**  
  Contains all core sales-related data including order details, product info, promotions, customer IDs, pricing, etc.  
  This is the primary fact table used for modeling.

- **Date Table 1/ Date Table 2**  
  ⚠️ _Note: This file was not used directly in the Power BI model._  
  Instead, a **custom Date Table was created using DAX** for better control and to support features like dual date comparisons.  
  This CSV is included here only as a reference or in case someone wants to load a static date table manually.

## Notes

- The model follows a **Star Schema** where `ElectroHub_RawData.xlsx` acts as the Fact Table, and dimension attributes were extracted or related using Power BI transformations.
- The date table created using DAX includes necessary columns like Year, Month, Day, and supports time intelligence functions.

