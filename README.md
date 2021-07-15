# SQL Queries
  ## How to print duplicate rows in a table?
    1.  SELECT name FROM table1 GROUP BY name HAVING COUNT(*) > 1
    
  ## Create, Drop, and Backup database Query:
    => CREATE DATABASE databasename;
    => DROP DATABASE databasename;
    => BACKUP DATABASE testDB
       TO DISK = 'D:\backups\testDB.bak';
   
  ## Create table, alter and drop table
    => CREATE TABLE table_name (
          column1 datatype,
          column2 datatype,
          column3 datatype,
         ....
      );
     => DROP TABLE table_name;
     => The ALTER TABLE statement is used to add, delete, or modify columns in an existing table.
     => The ALTER TABLE statement is also used to add and drop various constraints on an existing table.
     => 
