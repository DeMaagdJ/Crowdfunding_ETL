# Crowdfunding_ETL


Project 2:  ETL Mini Project

Fundamentals in Extraction, Transforming, and Loading Data

Authors : Geetha Rajendram, Elisangela Jardim, Kurt Goesch, Justin DeMaagd

Background:

In today’s world, data analysis has become integral component in many facets of business operation, social awareness, and technology innovation.  The more we can interpret data to better provide information to stakeholders, and other people of interest, the more productive we become, and the drive for improving daily processes can be streamlined quicker, more efficiently.  In efforts to better streamline data, it is accustomed to compile raw data (the initial collection of information) into a format that is usable by others. This data needs to be relatively easy to understand, and conclusive in its results.  In many cases, data may have different sources (i.e. html, API, SQL, Excel, etc.).  The skills to extract data from its source, then run it through a data pipeline are greatly valued by others who need this information transformed into more comprehensible material.  Data that will be better accustomed by the end user.  

In this exercise we showcased our ability to extract, transform, and load data from a crowdfunding dataset.  We successfully developed a methodology to present the flat data coherently into a relational database.

Methodology:

Extract and transform crowdfunding.xls and category.xls into *.csv

Utilizing the Pandas library, we created data frames for all:

•Category and Subcategory 

•Campaign 

•Contacts 


Import *csv files into SQL Server to create a relational database.


•All *.csv files were imported into a SQL Database scheme called Crowdfunding_db_schema.sql - The Contacts table was created by Option 1 (Use of Python Dictionaries)

•An entity relational diagram was created in postgres to illustrate and describe the relationships between the tables.

•Primary keys and foreign keys were assigned appropriately.
	
![CrowdfunfingERD_Screenshot](https://user-images.githubusercontent.com/119906575/225793568-348b8081-75bb-4be1-a8d6-bf44c98d7673.png)

•Database integrity was validated by running a SELECT Query for each table.
	
   <img width="205" alt="Category Select" src="https://user-images.githubusercontent.com/119906575/225793385-fdcc0f6e-ae9d-42ac-8395-3de3b30a7ae4.png">
   <img width="219" alt="Subcategory Select" src="https://user-images.githubusercontent.com/119906575/225793412-7c25d50c-35c4-42f7-93e2-afaf90f106b3.png">
   <img width="575" alt="Campaign Select" src="https://user-images.githubusercontent.com/119906575/225793301-3ef780df-067f-4118-aa4e-2c69c7ebc1b4.png">
   <img width="577" alt="Contacts Select" src="https://user-images.githubusercontent.com/119906575/225793440-da03ab9b-74ff-4912-9a5a-3d1220e5b355.png">
