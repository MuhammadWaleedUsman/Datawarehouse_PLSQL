# Datawarehouse_PLSQL
﻿#Establish the connection of the oracle SQL Database with the client using the connection configuration


Step1: Creating the Data warehouse:
 For the Data warehouse creation, run the script which is named as createDW.sql. This will create the tables in the data warehouse, such that dimension tables, fact table. After the data warehouse is loaded check that the 



Step2: Loading the the data into Data warehouse using the INLJ algorithm:

Run the SQL script file name INLJ.sql to load the transaction data into the data warehouse tuple by tuple using the cursor in plsql. While loading the data the factsales are also updated.



Step3: OLAP queries execution:

Run the SQL script file name queriesDW.sql to run the OLAP queries.
