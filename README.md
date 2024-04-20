![Logo](ss/tableau.jpeg)
# Tableau-Challenge

## Background 

Congratulations on your new job! As the new lead analyst for the New York Citi BikeLinks to an external site. program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicise and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilisation. Each month, bike data is collected, organised, and made public on the Citi Bike DataLinks to an external site. webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

## Data Preparation

Prior to any analysis in Tableau, the data sourced from February 2024 and March 2024 underwent cleanup using Pandas to improve readability. Both datasets were cleaned to ensure consistency and accuracy, and then merged together to create a unified dataset for further analysis in Tableau.

Data conversion included the following:
* Removal of ride_id column as it was irrelevant.
* `rideable_type` was converted to C - classic bike and E - Electric bike.
* Dropped columns which had missing values.
* Adjusted datatypes for consistency.
* Merged the file together for smoother loading into Tableau.

All of those changes are provided in `data_conversion.ipynb`

## Analysis
The following fields have been studied:
* Trip analysis by member type - giving insight of the type of membership and average trip distance.
* Analysis by bike type, month and type of membership - clearly stating what type of bike has been used for what type of membership and its fluctuations across given months.
* Top 10 starting stations. 
* Map for top 10 starting stations.
* Top 10 ending stations.
* Map for top 10 ending stations.
* Usage based on weekday and time by type of membership across given months.
* Heatmap analysis to see the relation between above.

- After each major point dashboard with insights was created which then was combined into a story for furher discussion. 









