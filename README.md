Data Cleaning

Removed rows with missing CustomerID values to ensure unique customer tracking.

Filtered out cancelled transactions (identified by InvoiceNo starting with "C") to maintain data accuracy.

Removed records with negative or zero Quantity or UnitPrice, which indicated invalid sales.

Created a new column TotalAmount by multiplying Quantity × UnitPrice for revenue calculations.

Converted InvoiceDate to proper datetime format for calculating recency.

Verified and removed duplicate records, if any, to avoid skewed metrics.
