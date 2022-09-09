# big-data-challenge

Assignment: Perform ETL on big datasets using PySpark.

Datasets used are Amazon's public product reviews, available at:
[review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)

The two datasets used here are the 'Office Products' and 'Electronics' datasets.

## ETL Process
- Extracted two s3 datasets using PySpark, in Google Colab Notebooks
- Counted all rows in each dataset (over 2 million rows in both datasets)
- Transformed dataset to fit predetermined table templates [schema file](../Resources/schema.sql), for use in SQL queries
- Confirmed and changed datatypes to match table templates
- Loaded data into an RDS instance as tables