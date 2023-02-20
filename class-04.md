# Class 04 Reading Notes

## nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?

  The best fit for complex query intensive environment is SQL databases.

2. What type of database is the best fit for hierarchical data storage?

  The best fit for hierachical data storages are NoSQL databases.

3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.

  NoSQL are better databases for unstructured data. NoSQL databases are much more felxible when it comes to theur schema, "well what is a schema?" a schema is a way to help us organize information. Therefore SQL databases are much better for complex data because they use schemas and are much more strict and organized.

## SQL Modeling Techniques

1. A one to many table is an entry in a table that can be connected to more than one entry in another. We can relate to them because our server can be connected to many tests, I think is a good example for this.

2. Prior to designing your relational database, it might be useful to ***make a UML*** of the database tables and their relationships.

3. The Primary key is to indentify each row in the table, there is usually only one but there can be more. The foreign key is there to match a primary key, matching these two together is what makes the database come togethere as a whole.

## SQL vs NoSQL

1. How do we treat keywords and parameters differently in SQL syntax?

  These allow us to create our tables and add in our data. We can select which table we would like to retrieve our data from. There is many commands such as update, create, delete and retrieve so CRUD. The keywords and parameters allow us to do this.
2. Define normalization within the context of schemas and data.

  It is that all records have to follow a certain schema and every piece of data that will be brought in has to fit to that table.
3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

- One-to-One: This is where in a table one user will have oen contact data based upon the example shown. It is when there is a one to one relation of data and they will typically or should share the same corresponding ID.
- One-to-Many: This is where One user could have multiple contact datas in the database based upon the example. It is when multiple pieces of data in a database can be shared with the same ID of "user" in this example.
- Many-to-Many: This is when two tables could be joined together and in this exmaple one user could have many roles and a role could have many user, this would need another table and it would create the connections for the two tables.

### ReadME

- I am late to this reading and have already completed this lab and code challenge so I don't necessarily have goals for this part. My goal for future would to become more comfortable navigating psql.
