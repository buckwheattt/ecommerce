# Data Quality Examination
## Overview  
This project designs five data quality checks for the E-Commerce Data dataset.  
Work was done using PostgreSQL in IntelliJ IDEA, with data imported from a CSV file.

## Data Quality Checks  
Completeness – Ensures each record has a CustomerID. (Critical)  
Validity – Checks that quantities and prices follow business logic for sales and returns. (Critical)  
Uniqueness – Detects duplicate InvoiceNo values. (Critical)  
Timeliness – Ensures InvoiceDate is not in the future. (Critical)  
Accuracy – Validates consistency between InvoiceNo type and Quantity sign. (Critical)

## Summary  
These checks cover the key data quality dimensions — completeness, validity, uniqueness, timeliness, and accuracy — to ensure the dataset’s reliability for analytics and reporting.
