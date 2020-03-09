# ETL-Project 
Proposal

Coronavirus Datasets (ETL Project)
________________________________________

Project Members: 
●	Alex Ledger
●	Andy Shi
●	Edith Jimenez
●	Rohan Kancharla
●	Joseph Picca

Overview
We plan to utilize South Korean coronavirus data from kaggle.com, with two primary datasets, one involving patient metadata and another involving patient movement data.

Finding Data
Data Source: https://www.kaggle.com/kimjihoo/coronavirusdataset

Data Cleanup & Analysis
-	All of our data’s original format is in .csv files.
-	We plan to merge our patients file with our routes file via the patient ID column
-	We also plan to create new data via transformations on the columns
-	These transformations will be performed in Python/Pandas

Final Database
-	The joined data will be loaded to a postgres database via pandas.

Potential Extra Work
-	Create a front-end web visualization with statistics from the dataset
