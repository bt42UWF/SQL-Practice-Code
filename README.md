# SQL-Practice-Code
### SQL Course Assignment

*This code is practice from a class assignment.*

This code is interacting with a relational database, creating tables, inserting data into them, and performing various queries. Here's a breakdown of each part:

1. Creating Tables:
   - Two tables are created: Pilot and Certification.
   - Pilot table has columns: PilotID (Primary Key), Name, and State.
   - Certification table has columns: CertificateID (Primary Key), PilotID (Foreign Key referencing Pilot table), and Certification_Level.

2. Inserting Data into Tables:
   - Fake data is inserted into both Pilot and Certification tables. The Pilot table gets data for pilots, and the Certification table gets data for pilot certifications. Certification levels are assigned: 1 for
   - Student Pilot and 2 for Professional Pilot.

3. Selecting Data from Tables:
   - The SELECT statements are used to fetch data from the Pilot and Certification tables. These statements retrieve all columns from each table.

4. Using AdventureWorks Database:
   - The code switches the database context to AdventureWorks for the following queries.

5. Querying SalesOrderDetail Table:
   - A query selects SalesOrderID, SalesOrderDetailID, ProductID, and OrderQty from the SalesOrderDetail table in the Sales schema.

6. Querying SalesOrderHeader Table:
   - Another query selects SalesOrderID and TerritoryID from the SalesOrderHeader table in the Sales schema.

7. Joining Tables and Aggregating Data:
   - Two queries join the Production.Product table with the Sales.SalesOrderDetail table to retrieve information about products and sales orders. The first query retrieves ProductName, ProductID, OrderQty, and SalesOrderID. The second query retrieves ProductName, ProductID, and total OrderQty grouped by ProductID.

8. Aggregate Functions:
   - One last query selects a single SalesOrderID from the SalesOrderDetail table, and calculates the total OrderQty and the average UnitPrice for that particular order.
