# Data-Glacier-Week6

Following steps are done in File_ingestion.ipynb 

1. 2+ GB csv file downloaded from https://www.kaggle.com/datasets/hhs/health-insurance-marketplace?select=Rate.csv  

2. File read using different methods of file reading eg: Dask, Modin, Ray, pandas 

3. Computational efficiency reported for the above methods

4. Basic validation on data columns like removing special character , white spaces from the col name etc. performed 

5. A YAML file created with the column names of the csv file

6. Number of columns and column name of ingested file validated with YAML

7. File written in pipe separated text file (|) in gz format.

8. A summary of the file created
