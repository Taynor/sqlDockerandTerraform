# SQL Server on Docker provisioned with Terraform
Create a local Docker image of SQL server 2019, using Terraform to optionally upload the image to an Azure container instance. 

The purpose of the solution is to convert a local SQL .bak file to .bacpac file. Upload the file to an Azure file share, where it can be imported into the readily provisioned Azure SQL Database.

To download the latest version of SQLPackage go to the Microsoft site:

https://docs.microsoft.com/en-us/sql/tools/sqlpackage/sqlpackage-download?view=sql-server-ver15

The example uses the AdventureWorks databases as reference point. To download the latest version of the AdventureWorks database, go to the following Microsoft site:

https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms
