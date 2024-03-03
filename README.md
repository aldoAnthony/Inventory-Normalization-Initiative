<h1>Inventory Management Database Normalization Project</h1>

<h2>Description</h2>
This project focuses on normalizing the inventory management database for a wholesale business. The initial database structure comprised two denormalized tables, leading to inefficiencies and data inconsistencies. The primary objective is to transform the database into the third normal form (3NF) to enhance data consistency, eliminate redundancies, and prevent anomalies.

The motivation behind this project is to streamline the inventory management process for the wholesale business by establishing a well-organized and optimized database structure. By normalizing the database, we aim to improve data integrity, simplify data management tasks, and enhance overall system performance.
<br />


<h2>Language and Libraries Used</h2>

- <b>Python</b> 
- <b>Pandas</b>
- <b>SQL</b>
- <b>SQLite3</b>
- <b>SQLAlchemy</b>
- <b>sql_magic </b>


<h2>Environments Used </h2>

- <b>Jupyter Notebook</b> 

<h2>Project Workflow:</h2>

- **Exploration of Denormalized Tables:** Initially, I explored the denormalized tables using SQL queries to identify data inconsistencies, anomalies, and redundancies.
-	**Normalization to 1st Normal Form (1NF):** Following the Entity Relationship Diagram (ERD) that was provided as a guideline, I created and populated tables to conform to 1NF. This involved organizing data into separate tables to eliminate repeating groups and ensure atomicity.
-	**Conversion to 2nd Normal Form (2NF):** In transitioning from 1NF to 2NF, I ensured that all columns in each table were fully functionally dependent on the primary key. This required creating unique identifiers and breaking down tables to remove partial dependencies.
-	**Addressing Data Anomalies:** I identified and removed erroneous data entries to enforce foreign key constraints and maintain data integrity between tables. This involved working closely with the data owner to rectify errors and ensure consistency.
-	**Client Use-Case Requirements:** To meet project specifications, I removed any entries from tables that were of no use. This ensured ease of use for the client and streamlined data usability.
-	**Conversion to 3rd Normal Form (3NF):** Finally, I constructed remaining tables to achieve 3NF, ensuring each table contained only non-transitive dependencies and was logically organized for efficient data management.
  




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
