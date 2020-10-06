# Customer Segmentation & Cohort Analysis For Uk-based non-store Online Retail

The goal of this project is to create customer segments for a UK-based non-store online retails using **Recency, Frequency, and Monetary** segments.

## Data:

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

**Features**
- `InvoiceNo`: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- `StockCode`: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- `Description`: Product (item) name. Nominal.
- `Quantity`: The quantities of each product (item) per transaction. Numeric.
- `InvoiceDate`: Invoice Date and time. Numeric, the day and time when each transaction was generated.
- `UnitPrice`: Unit price. Numeric, Product price per unit in sterling.
- `CustomerID`: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- `Country`: Country name. Nominal, the name of the country where each customer resides.

## Steps:
1. Preprocessing
     - Clean Missing Data and remove duplicates
2. Make Cohort Analysis
3. Create Retention Rate Table
4. Create and Analyze RFM Segements
5. Implement K-Means Clustering
