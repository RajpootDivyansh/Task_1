## Dataset Summary

This dataset contains 9,800 records of customer orders including details about order IDs, shipping methods, customer and geographic information, product details, and sales amounts. It is structured to support analysis in customer segmentation, sales performance, and shipping efficiency.

### Key Features:
- **Order Details**: Order ID, Dates, Ship Mode
- **Customer Info**: Customer ID, Name, Segment, Region
- **Product Info**: Product ID, Category, Sub-Category, Name
- **Geography**: City, State, Postal Code
- **Sales Metrics**: Sales amount per line item

### Cleaning Steps:
- Converted date columns to datetime format
- Handled 11 missing values in Postal Code
- Removed any duplicates if found
- Optimized data types for better performance
