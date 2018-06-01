# imdb-database-model
Designed and populated IMDB database in MSSQL, Oracle and MySQL using Toad Data Modeler to return results of searches by user, write reviews and vote for polls
<br/> [View Data Model](https://github.com/vighneshvnkt/imdb-database-model/blob/master/Oracle%2011g%20Release%201.png)

## Running the example

For MS-SQL
```
1) Run the MSSQLIMDB.sql script file to create table and add dependencies of foreign keys and other relations
2) Insert all data in the Data folder either by importing from excel file or by running insert queries
3) Run triggers and stored procedures from the Triggers folder
4) Run select queries from views folder to see appropriate results and test the triggers and other dependencies
```
For Oracle
```
1) Run the OracleIMDB.sql script file instead of MSSQLIMDB.sql to create tables
Steps 2 to 4 are similar to MS-SQL
```

## Authors

* **Vighnesh Venkatakrishnan**
* **Naini Shah** 
* **Fiona Lobo** 
