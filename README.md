# PayCor repository

PayCor repository has two files:
- Packages.zip contains NuGet packages.
- WebAPIApplication.zip contains ASP.NET Web API project and test pages (developed in MS VS 2015).

Web API is developed against AdventureWorks2012 database (restored and browsed with MS SQL Server 2012 database). 
EntityFramework 6.1 is used for DB connection and DB Objects accessing. (Database-First Approach)

In order to test the Web API REST service please change DB connection string with name AdventureWorks2012Entities in web.config file. 
Run the project and please use ProductClient.html and PurchaseClient.html to test WebAPI REST service.
