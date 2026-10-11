# PySpark Projects
 
Data engineering projects in PySpark built on the [2015 Flight Delays and Cancellations](https://www.kaggle.com/datasets/usdot/flight-delays) dataset from Kaggle.
 
## Projects
 
| Project | Description | Key topics |
|---------|-------------|------------|
| PySpark Medallion Architecture: E2E Pipeline | Full pipeline from raw CSV files to a star schema and business analytics | Bronze/Silver/Gold layers, data quality tests, SCD2 dimensions, fact table with point-in-time lookups, feature engineering |
| PySpark SCD2: Production-Ready Approach | Standalone, step-by-step Slowly Changing Dimension Type 2 extracted from the pipeline above | Row hash change detection, surrogate keys, validity ranges, UNKNOWN and QUARANTINED members |
 
## Tech stack
 
PySpark, Parquet, Kaggle Notebooks
