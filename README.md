# SQL Server and R In Practice

## Installing additional packages
To use the forecast package, I need to add that package to SQL Server
1. Find the Rgui.exe within your SQL Server installation. In the docs, the most probable location is
```sh 
C:\Program Files\MSSQL14.MSSQLSERVER\R_SERVICES\bin\x64
``` 
I'm using SQLEXPRESS, but you can find the file. From there, you'll open an R Environment. 
To install the package(s):
```sh
install.packages("forecast")
```