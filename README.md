Scale Azure SQL Data Warehouse
==============================

            
Scale Azure SQL Data Warehouse

This is a simple runbook that will allow you to scale your Azure SQL Data Warehouse.


Depending on your goals with Azure SQL Data Warehouse, at time it is important to scale up and down depending the incoming workload or amount of data. In Automation, you can schedule or call a webhook depending on your needs. 

Scaling Concerns

Much like pausing an Azure SQL Data Warehose it is important to check to see if request are processing before issuing a scale operation. Since the data warehouse effectively pauses for the scale operation, running processes that have data movement can cause
 the operation to take a considerable amount of time.


This is designed to be used from an Azure Automation Account, but can be altered to be ran from other locations.


 




 




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
