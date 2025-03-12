# Revenue Dashboard in Power BI
![Revenue Dashboard Banner](https://raw.githubusercontent.com/Mangaleshwaran2002/Revenue-Dashboard-in-Power-BI/refs/heads/master/Dashboard.png)
## Overview
This project showcases a **Revenue Dashboard** built using Microsoft Power BI, leveraging a dummy store dataset stored in an Excel file. The dashboard provides insightful visualizations and analytics based on customer and order data, enabling users to track revenue, order trends, and customer distribution effectively.

---

## Dataset Description
The dataset is stored in an Excel file with two sheets: **Customers** and **Orders**. These sheets are linked in Power BI using the `Customer ID` field as the common key.

### Customers Table
This table contains customer-related information:
- **Customer ID**: Unique identifier for each customer
- **Customer Name**: Full name of the customer
- **Phone**: Contact number of the customer
- **Address**: Street address of the customer
- **City**: City of residence
- **State**: State of residence
- **Zip**: Postal code
- **Country**: Country of residence

### Orders Table
This table contains order-related details:
- **Order ID**: Unique identifier for each order
- **Customer ID**: Links to the Customers table
- **Rush Shipment**: Indicates if the order was expedited (Yes/No)
- **Cookies Shipped**: Number of cookies shipped in the order
- **Revenue**: Revenue generated from the order
- **Order Date**: Date the order was placed (Note: This field appears twice in your description; assuming it's a typo)

---

## Procedure
The dashboard was created using the following steps:

1. **Data Import**:
   - Imported the Excel file containing two sheets (`Customers` and `Orders`) into Power BI.
   - Ensured proper data types and formatting for all columns.

2. **Data Modeling**:
   - Established a relationship between the `Customers` and `Orders` tables using the `Customer ID` field as the primary key.
   - Verified the relationship integrity to ensure accurate data aggregation.

3. **Dashboard Design**:
   - Created a visually appealing dashboard in Power BI.
   - Used various visuals such as charts, tables, and slicers to represent key metrics like total revenue, orders over time, customer distribution by city/state, and rush shipment analysis.
   - Applied conditional formatting and custom themes for a stunning look.


---

## Tools Used
- **Microsoft Power BI**: For data visualization and dashboard creation.


---

## How to Use
- Ensure you have [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
1. Open the `.pbix` file in Power BI Desktop.
2. Ensure the Excel dataset is placed in the same directory as the `.pbix` file (or update the data source path if needed).
3. Explore the dashboard by interacting with slicers, filters, and visuals to analyze store performance.

---

## Screenshots
![Revenue Dashboard Banner](https://raw.githubusercontent.com/Mangaleshwaran2002/Revenue-Dashboard-in-Power-BI/refs/heads/master/Dashboard.png)


---

## Author
Created by K.Mangaleshwaran on **March 12, 2025**.

---

## License
This project is for demonstration purposes only and uses dummy data. Feel free to adapt and use it under the MIT License.