# London-cycle-rental-analysis

This project aims to perform bike rental trends analysis using real-world Transport For London (TFL) dataset (https://cycling.data.tfl.gov.uk/). The analysis aims at extracting crucial insights, suggest business recommendations, explore different Data Science use cases, and ultimately create a simplistic model that demonstrates the application of
data science to this business. 

Just a quick note if you wish to run the SQL queries - all the SQL queries have been run on an online SQL Server editor named https://onecompiler.com/sqlserver/, which follows built-in MM-DD-YYYY formatfor datetime columns, which could pose an issue while insertion, as for my data is in DD-MM-YYYY, and so is my insertion code. I tested this using a 15-record sample set of entire dataset, so it was okay for me once I figured out the problem. If someone wished to insert the entire dataset, please note that this can be easily fixed using any varchar to datetime conversion code, which can be easily retrieved online. 

Please find the complete Python notebook and SQL queries within this folder used to do the analysis. 
