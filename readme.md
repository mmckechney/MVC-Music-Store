# MVC Music Store Sample App (Containerised)

This is a copy of the original MVC Music Store demo application from ~ 2010 that was built to demonstrate how to with the (at the time) new ASP.Net MVC framework.

You can find the full documentation on how to build this solution online on [Microsoft Docs](https://docs.microsoft.com/en-us/aspnet/mvc/overview/older-versions/mvc-music-store/mvc-music-store-part-1).

The purpose of this fork is to demonstrate how we can bring this solution to Windows Containers.

>>Note: if you want to run this sample you will need a separate SQL Server (or Azure SQL DB) instance where your database can be hosted. You will also need to define a Windows environment variable called 'MusicStoreEntities' and set its value to the .NET Connection String of the SQL database. See the associated blog for more details.
