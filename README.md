Hello Git, it is Mylo.

# Project Summary

This is the project of transforming the data from csv files to the final DWH. It includes the information from imigration data, demographic data, and temperature data; with the purpose of giving the user some specific information.

# Scope of the Project

Project goal is to check whether there is relationship between the number of airports, foreign born people with the number of visits from the foreign countries.

Data which will be used in project:
- airport-codes_csv.csv
- I94_SAS data
- us-cities-demobraphics.csv

Based upon this data dwh will be made with fact and dimension tables.

## Tools used in the process:
- AWS S3: data storage
- AWS EMR: data processing with PySpark
- AWS Redshift: data warehoue and data analysis

## Detailed info regarding the data
- I94 Imigration Data; sas format; data set with the info of U.S. visitations from overseas (all modes) and Mexico air and seat travelers.
- U.S. Demographic Data; csv format; data set of infromation about the demographics of all US ciries and census-designated places with a population greater or equal to 65.000
- World Temperature Data: This is the data regarding the demperature in the cities all around the World

# Explore and Assess the Data

## Explore the Data
- pandas library is being used for the exploratory anlysis of the data sets
- with data frame head function we take a look on the data in the files
- necessary column are picked from each data file for the purpose of further analysis

