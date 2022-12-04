# Data Modeling

## nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?
For complex queries: SQL databases are good fit for the complex query intensive environment whereas NoSQL databases are not good fit for complex queries.

2. What type of database is the best fit for hierarchical data storage?
 NoSQL database fits better for the hierarchical data storage as it follows the key-value pair way of storing data similar to JSON data.

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
For scalability: In most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server. On the other hand, NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.


## sql modeling techniques

1. Among data tables, what is a one-to-many relationship and how do we “relate” them?
you can use notation to specify the cardinality of a relationship.

2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
You can use these to enforce a match between the foreign key and primary key. A foreign key is a set of values in a table which match to the primary key of another table.  There isn’t a command to define a foreign key, per se, the existence of columns with the proper data is the minimum requirement.

3. Explain the difference between a primary and foreign key.
Primary key is the general term for any set of values that are unique and non-null across a table.  They provide a means to identity one record in a table.  A compound primary key is a primary key made up of two or more columns.


## sql vs nosql 

1. How do we treat keywords and parameters differently in SQL syntax?
we use the key words to determin what we want to do before we enter the info we want to 

2. Define normalization within the context of schemas and data.
Database normalization is the process of organizing data into tables in such a way that the results of using the database are always unambiguous and as intended. Such normalization is intrinsic to relational database theory.

3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
one to one is like a serial number on a product it is assinged to aa product but a different number. one to many a user can be part of many contact data. and many to many you cant predict what the user is so you have to add a user roll to relate the data


