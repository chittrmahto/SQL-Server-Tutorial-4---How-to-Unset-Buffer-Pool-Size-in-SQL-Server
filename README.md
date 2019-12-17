# SQL-Server-Tutorial-4---How-to-Unset-Buffer-Pool-Size-in-SQL-Server
SQL Server Tutorial 4 - How to Unset Buffer Pool Size in SQL Server


Steps: ---
1. Open Sql Server Management Studio.
2. Connect SQL Server with credentials.
3. Check Folder for Buffer Pool (Folder Name - 'SQLSVRCACHE' in your location) which is created in previous video. And Buffer file is already created.
4. Run the below Query in Query Window
 
 USE master
 GO

5. Run below Query for buffer pool off.

 ALTER SERVER CONFIGURATION
     SET BUFFER POOL EXTENSION OFF;
 GO
 
 
 Video URL : https://chittranjanmahto.blogspot.com/2019/08/sql-server-tutorial-4-how-to-unset.html
