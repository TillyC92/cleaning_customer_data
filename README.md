# cleaning_customer_data
Project to demonstrate cleaning data and changing data types

Scenario:
You have been asked to create a DataFrame that stores the data in customer_train.csv much more efficiently.

The following key changes were identified: 

Columns containing categories with only two factors should be stored as Booleans (bool).
Columns containing integers should be stored as 32-bit integers (int32).
Columns containing floats should be stored as 16-bit floats (float16).
Columns containing nominal categorical data should be stored as the category data type.
Columns containing ordinal categorical data should be stored as ordered categories, and not mapped to numerical values, with an order that reflects the natural order of the column.

Also filtered to only contain students with 10 or more years of experience at companies with at least 1000 employees, as their recruiter base is suited to more experienced professionals at enterprise companies.

If you call .info() or .memory_usage() methods on ds_jobs and ds_jobs_transformed after you've preprocessed it, you should notice a substantial decrease in memory usage.
