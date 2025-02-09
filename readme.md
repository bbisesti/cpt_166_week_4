# Weekly Assignment Instructions


### Overview

This week we will be working on architecting our databases more efficiently, or, to put it in database terms - "Normalization"!  Normalization is the process of ensuring that we are storing our data in the most efficient way in a relational database.  

### Learning Outcomes

By the end of this week you will be able to take "un-normalized" tables and perform a "database schema migration" to convert them to more efficient, "normalized" architecture utilizing primary and foreign keys!

### Instructions
1. **Review the following materials**:

   - [W3Schools Database Table Manpiulation](https://www.w3schools.com/sql/sql_create_table.asp)
  
     Please read topics "Create Table" through "SQL Foreign Keys" under this W3schools tutorial.  This will review table manipulation queries as well as define what Primary and Foreign keys are and how they are helpful!  Understanding this concept will help significantly in determining how you go about creating normalized tables!  

   - [Normalization in SQL](https://www.datacamp.com/tutorial/normalization-in-sql)

     Datacamp is a really popular website which is used to learn Data skills!  This particular page servers as an excellent introduction to the concept of what normalization is and why it's important!

   - [Database Schema Migrations](https://www.liquibase.com/resources/guides/database-schema-migration#:~:text=Database%20schema%20migration%20is%20the,to%20evolve%20alongside%20the%20application.)
  
    This liquibase (a tool used for "change management - i.e. tracking changes across databases or code) article provides a really in-depth description of what a database sechema migration is and how to best go about performing one!  We will be doing this manually in this assignment but there are tools that help make this a lot easier in the real world!

3. **Complete the following tasks**:

   - Please Download this repository to your local machine adn run the "1.sql" into your Postgres cluster.  This should create a table called "students" in your postgres -> public (db-schema) unless otherwise specified by you when you run it.
     
   - Next, after reading through the materials above please update the "2.sql" with the multiple scripts you need to write to perform your "Databsae schema migration" from this un-normalized (messy) table to several cleaner tables in at least 3rd normal form!  I'd HIGHLY recommend re-naming the current "students" table so you can re-create the new "students" table with appropriate keys which your other tables can reference.
  
   - Once your 2.sql has been updated to your satisfaction with your database schema manipulation queries as well as the data migration queries please publish your updated repository to your public Github profile and submit the link in Brightspace!
