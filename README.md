# Data-Extract-Transform-Load-Project

# Introduction 

This Projectm involved us focusing on two different sets of data comprising off Crowdfunding Data and Contacts Information. These files were in the form of CSV Files. The goal of the project was to use Extract, Load and Transform processes to consolidate information and restructure to desired data relationships in the form of new DataFrames/Tables.

# ***Files***
## *README*  
File summarising the information regarding the project.
## *ETL_Project_JUPN* : 
Completed Jupiter Notebook file containing the solutions in which the outputs, schema and ERD information was obtained from.
## *Resources*
Folder containing the CSV files used in this Anlaysis.
## *Output*
Contains DataFrame's of results from the notebook exported as CSV files.

# ***Analysis***

## Extract 
This involved extracting the two CSV files and examining both files to see what data types and information we were working with.

![Alt text](Images/dependencies.png) 
![Alt text](Images/Customer%20info.png)

## Transform
Many of the columns contained specific pieces of information we required to be in seperate DataFrames to which we need to tranform and concatinate into specific Dataframes:
image.png
Category and Subcategory DF's were required from the initial crowdfunding csv.
![Alt text](Images/campaign%20DF.png)![Alt text](Images/subcategory_DF.png)


![Alt text](Images/Changing_data_format.png)


