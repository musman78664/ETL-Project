# ETL-challenge
# Purpose
The purpose was to extract data from multiple source systems, transforming it to suit business needs, and load it into a destination database 

# Extraction
Data source 1 - https://catalog.data.gov/dataset/2016-apd-traffic-fatalities 

Data source 2 - https://catalog.data.gov/dataset/2017-apd-traffic-fatalities

# Transform:
Perform joins for the two datasets and drop irrelevant columns. Clean column names. Get rid of field with missing data.

# Load:
We used sqalchemy to store the data into the PostgresSQL database. We chose PostGresSQL because it saves us time to upload tables.

# How to use 
The "Data" Folder contains the data from mentioned in Extraction

To analyze the cleaned data, clone the repository and run "Extract and Transform Code.ipynb". 

# Team Project Members
Loretta Cortez - https://github.com/lorettac953

Prerak Patel - https://github.com/prerak-patel

Kensuke Suzuki - Owner

Mohammad Usman - https://github.com/musman78664



