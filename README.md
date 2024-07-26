# Term2-W1-Thursday

# Intro to database

## Relational Models

- Logical represention of Data model:

- Tables: A collecion of related data orgnanized into rows and columns:

- Rows: Records 

- Collumns: Fields or attributes (features of the table)

- Example: Student Table

## Primary and Foreign Keys

- ERD (Enitity Relationship Diagram)

# Database

- Used files to store data before (txt, json, csv)

## What is Database?

- Definition: An organized collection of data.
- Purpose: Store, manage, and retrieve data effciently. When you have to refer back to the data it is easier to access when it is orgnaised. Manging could be editing, moving or updating data.
- Examples: Student records, inventory, customer information.

# Types of Databases:

- Relational: Tables with rows and columns. A collection of tables.
- Hierarchial: Tree-like structures. (Is used in Hierarchial data bases)
- Network: Complex relationships.
- NoSQL: Flexiable data models

# Why Database?

- Data Integrity: Ensuring data accuracy and consistency.
- Data Security: Protecting data from unauthorized access.
- Data Sharing: Multiple users accessing data simultaneously.
- Data Backup and Recovery: Protecting data from loss.

# Relational Database

- Based on the relational model. 
- Orgnaized into tables.
- Relationships between tables.

Examples: School database has tables for teachers, students, courses, etc.

# Advantages of Relational Database

- Data independence 

- Flexible 

- Scalable

- ACID Compliance (Key advantages)

# What is ACID?

## Atomicity

- All database operations are treated as a single unit

- Either all operations are completed or none are 

- Example: Bank transaction (deposit or withdrawl)

## Consistancy 

- Database transitions from one valid state to another

- Data integrity is maintained

- Example account balance remains correct after a transaction.

## Isolation

- Concurrent transactions fo not interfere with each other

- Each transaction sees a consistent view of the data base

- Example: Muliple users accessing the same data.

## Durability

- Commited transactions are permanently stored

- Data is not lost in case of system failure.

- Example: Database backups and recovery.

# Disadvatages of Relational Database

- Performance issues with large datasets

- Complex schema design (If your data base schema design is complex will have certain limitations and won't work to the optimal level)

# Database Management System (DBMS)

- Software that is used to control and manage data access.

- Organsied and a safer way to use Database.

- Database Administrator is reponsible for the system. 

- Examples: MySQL, Microsoft Access, Oracle, PostgreSQL, etc.

# Structured Query Language (SQL)

- Standard language for managing reltional databases.

- Used for: data definition, manipluation, and control. 

## Data Definition Language (DDL)

- Methods: Create, modify, and delte database structures.

## Data manipulaton Language (DML)

- Insert, update, delete, and retrieve data.

## Data Control Langauge (DCL)

- Grant and revoke user permissions. (Incase the database is used by multiple people)



