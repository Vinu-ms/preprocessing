# preprocessing
Filled missing values in Income with the median.

Removed duplicates to keep only unique rows.

Standardized text in Education and Marital_Status (e.g., Graduation → graduate, Together → married).

Converted dates (Dt_Customer) into proper datetime format.

Renamed columns to lowercase with underscores for consistency.

Fixed data types (year_birth as int, income as float, dt_customer as datetime).

The cleaned dataset has the same rows and columns, but is now consistent, complete, and analysis-ready.
