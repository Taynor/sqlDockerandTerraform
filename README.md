# sqlDockerandTerraform
Create a local Docker image of SQL server 2019, using Terraform to optionally upload the image to an Azure container instance. 

The purpose of the solution is to convert a local SQL .bak file to .bacpac file. Upload the file to an Azure file share, where it can be imported into the readily provisioned Azure SQL Database.
