# Crowdfunding-ETL
# OverView of Crowdfunding_ETL
This module was to learn how to apply the extract, transform, and load (ETL) process, which are the three steps collecting, cleaning, and storing data in a database prior to performing analysis. Python and Pandas are used to perform the extract and transform steps. Then,  PostgreSQL database and table schemas are created by using an entity relationship diagram (ERD), and load the data into the database. Finally, SQL is used to perform data analysis.
# ELT Challenge
In order to complete module 8 challenge there were following 4 main parts to work on

* Extracting and transforming the data from the large Excel file into four separate CSV files

* Creating a PostgreSQL database and tables by using an ERD

* Loading the CSV files into the database

* Performing SQL queries to generate reports for stakeholders.
# Deliverable 1
In deliverable one first dependencies are imported and then data is extracted from a csv file and data was as follow.
![image](https://user-images.githubusercontent.com/112978144/214447739-e88b3e31-3f89-4ef2-be5c-64129b54239e.png)
* After creating the DataFrame the above data ordered in the following shape
![image](https://user-images.githubusercontent.com/112978144/214447976-7d70677f-c66a-4b58-bc79-dcf037526aeb.png)

# Deliverable 2
In deliverable 2 data is transformed and clean. After performing different steps the final shape of the data is as follow:
![image](https://user-images.githubusercontent.com/112978144/214448433-b5ae8f49-b0db-4ebf-87a6-a8c4d74cb4b6.png)

# Deliverable 3 & 4
In deliverable 3 and 4 schema is created and data is retrieved from the csv files and finally tables are exported to csv files. Following quary is made to get the data for deliverable 3 table
![image](https://user-images.githubusercontent.com/112978144/214450392-b36c8f05-8b5b-4f05-94fe-52074df6bb87.png)
# Final Discription
As it's stated in the module ETL is a flexible process for moving data. It can be as basic as a one-time migration from one database to another. Or, it can be as complex as an ongoing automated collection of messy, real-time data from many sources.

In the extract phase, data gets pulled from possibly diverse sources that are either internal or external. The sources might be flat files, scraped webpages in either HTML or JavaScript Object Notation (JSON) format, SQL tables, or even streams of sensor data stored on a hosted external cloud-based server. The extracted data gets held in a staging area that exists between the data sources and the data targets, like a PostgreSQL database, data warehouse, or data mart.
![data-8-1-1-3-transform-phase-cleans-and-structures-data](https://user-images.githubusercontent.com/112978144/214451078-e06bf1bb-8a45-4b8e-9a21-4c4f02b896e8.png)
