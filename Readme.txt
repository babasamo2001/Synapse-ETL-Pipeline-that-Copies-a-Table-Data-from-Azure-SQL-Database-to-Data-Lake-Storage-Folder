
 
  Project Title: Synapse ETL Pipeline that Copies a Table Data from Azure SQL Database to Data Lake Storage Folder

A.  Data Source: Azure SQL database table



B.  Target Details: 
	  Storage Resource: Data Lake
	  Number of Files: 1 (Dynamically created at runtime)
	  File Format: .parquet	

C.  Business requirments:
    Client (user) needed to copy a table data from Azure SQL Database to a Data Lake storage location
	

D.  Solution Steps: 
   	 -create RBAC role assignment for the storage account container 
   	 -create link service, datasets, ETL pipeline and activities
   	 -Copy files from source folder to the output folder
   	 -check the output folder to confirm the pipeline runs successfully


E.  Azure Services used: 
   	 -Azure Data Lake
   	 -Azure Data Factory
   	 -Azure SQL Database
