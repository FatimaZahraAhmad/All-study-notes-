Databases 1



database
a structured and organized collection of data that is stored electronically.
i.e, amazon.com utillize their sales data to make informed decisions about the products they should offer,

Structured Query Language (SQL)
a programming language used for displaying, sorting, filtering,and summarizing data in a database. Collectively, all those activities are known as querying.
display, sort, filter, summarize data.

Application programming interfaces (APIs)
sets of rules, protocols, and tools that allow different applications to communicate with each other

Graphical User Interface (GUI) A type of user interface through which users interact with electronic devices via visual indicator representations.

Data Raw, unprocessed facts and figures, typically organized in a structured format within ak database.

Metadata Data about data, which describes characteristics or relationships of the data./// 
Information Data in a context that gives it meaning.///

Flat File A data file that is not related to or does not contain any linkages to another file. 
MongoDB A popular example of a NoSQL flat file database that stores data in an object-oriented way./// 
Relational Database A database that has many tables, with shared common columns between tables. 
Spreadsheet A row-and-column grid in which structured data tables can be created.


Hardware The physical components such as the CPU, RAM, and storage devices on which a database runs. 

Software The operating system and the applications that manage the database and enable people to interact with it.

Database Management System (DBMS) Software that manages the database within the entire database system.

System Administrator A person who oversees the entire database/information system to ensure that everything is operating optimally. 
Database Designer A database architect of the database who ensures that it fits the business needs and functions optimally./// 
Database Administrator (DBA) A user of the database management system who ensures that the database is running correctly. 
System Analyst Designs and implements the application programs that interact with the database management systems./// 
End User The user of the applications to run the day-to-day operations of the organization.

Procedures Rules or policies about how the database is designed and used.

Data Known as “raw facts,” or the data we collect, like phone numbers or addresses.

Schema The structure of a database, including its tables and the relationships between them./// 
Non-Relational Databases Databases that do not use the traditional tabular relational model that is used in relational database management systems, 
some examples of non-relational databases are:

key-value stores, 
wide-column stores, 
graph stores, 
NoSQL databases, 

Document-Oriented Database A non-relational database that pairs a key with a complex data structure./// 
Key-Value Store A simple non-relational database that pairs each key with a single value. 
Wide-Column Store A non-relational database that allows the names and format of columns of its tables to vary from row to row.///
Graph Store A non-relational database that links data through edges, nodes, and properties.///

Transactional Database A database system designed for managing the day-to-day operations of an organization./// 
Analytical Databases A specialized type of database designed for storing, retrieving, and analyzing large volumes of data.///

Online Transaction Processing (OLTP) Databases Operational databases, which are used for handling real-time transactions daily.
ACID An acronym that stands for atomicity, consistency, isolation and durability of data.

Columnar Data Storage Storing data in columns rather than in rows.///

Parallel Processing The simultaneous execution of multiple operations across multiple CPU cores in a distributed computing environment to improve performance.///

Online Analytical Processing (OLAP) Software technology that is used to analyze business data from different points of view.///

Business Analytics The practice of using data analysis and statistical techniques to drive informed business decision making.///

Data Warehouse A backend enterprise-level system used for storing data that is used for analysis and reporting.///
Front End A user interface or application that enables users to interact with a database without directly interacting with the underlying DBMS.///
Back End The part of the database system responsible for managing and storing data.///

Hierarchical Models Databases that store data as records and organize them into a tree structure where one parent gets a lot of child connected to it. 
Network Model The database in the network model is similar to the hierarchical model except the data inside is more flexible and sent in a graph, linked through pointers. 
Common Business-Oriented Language (COBOL) A programming language for data processing for batch processing///

Object-Relational Database (ORDBMS) A type of database that supports complex data types such as arrays, nested table, and more.///

Object-Oriented Programming (OOP) Organizing computer programs around objects.
Object-Oriented Databases (OODBMS) A database model. when data is inserted in, it will enact
it as an object (like you see in js or python) and enter a key:value to it.///


XML Hybrid Database A database type that bridges the structured formatting of XML and the relational model of modern databases.///


NoSQL
a class of databases that enable the ability to store and get a lot of data in a flexible manner.///

Segment A structured set of data elements.///

SubSchema
The part of a database that applications interact with.////

Data Definition Language (DDL) Commands that create and remove schema components in a database./// 
Data Manipulation Language (DML) Commands that allow interaction with the data in a database.///

Relational Database Relational databases are databases that store data in tables. 

Relation Also known as a table, a row-and-column structure for holding data in a relational database. 
Tuple Also known as a record, one row in a relation (table) containing all the data for one item. 
Attribute A single piece of information within a column, also known as a field.

RDBMS Relational database management system.
Structured Query Language A programming language that allows data to be retrieved and manipulated in a relational database.

Columns The individual attributes of a table, also called fields. They are usually of the same data type and can contain various data, such as numbers, text, and dates. 
Constraints A rule that restricts the values that can be stored in a column or a table. Constraints are used to ensure the integrity of the data in a database. 
End-User Interface Where ordinary database users interact with the data. 
Foreign Key A column or a combination of columns that refers to the primary key of another table. 
Indexes A data structure that speeds up the retrieval of data from a table. Indexes are created on columns that are frequently used in queries. 
Primary Key A primary key is a column or a combination of columns uniquely identifying each row in a table. The primary key cannot contain duplicate values.

Encapsulation Groups data and operations that operate on it into a single entity. 
Inheritance OODM uses inheritance to organize and structure data models. For example, objects inherit attributes and methods from classes. 
Metadata Refers to descriptive and structural information providing context and data details. It describes various data characteristics, such as its format, source, quality, content, location, and relationships with other data.

Object-Oriented Data Model (OODM)
An object-oriented database model that organizes and represents data as objects, including both data and behavior.

Polymorphism Enhances OODM's code reusability, modularity, and flexibility. 
Object An organizing unit in object-oriented databases that includes a fact, information about the fact, and the relationships between facts. 
Class A grouping of similar objects with shared attributes and behaviors. 
Method An action that can be performed on an object to which it is assigned

Extended Relational Database Model (ERDM) Extensions of traditional relational database models that add enhanced functionality. 
Object/Relational (O/R) Database Model A type of database model that bridges the gap between object-oriented and relational databases by enabling objects to be directly stored and retrieved from the database.

JavaScript Object Notation (JSON)
a format used in databases, you can represent data in a good format.

Conceptual Data Model A high-level representation of a system's data requirements and structure that establishes the entities, their attributes, and relationships between entities in a relational database. 
Entity Relationship (ER) Model A visual representation that illustrates the structure and relationships within a database or data model.

Cardinality The number of instances of one entity (or table) that can be associated with a single instance of another entity (or table) through a relationship.

Associative Entity An entity that exists only to put data in one entity with data in another. 
Entity-Relationship Diagram (ERD) Used to visualize the relationships among entities (objects or concepts) in a system or database, as well as their structure, attributes, and interactions.

Chen Notation A visual representation technique for entity-relationship modeling that uses rectangles to represent entities, diamonds for relationships, and lines to represent cardinality and participation constraints.

Crow's Foot Notation A graphical representation technique that uses various symbols to represent cardinality, relationships, attributes, and relationships between entities, such as crow's feet, lines, and diamonds.

UML Class Diagram Notation A notation system that illustrates the structure and relationships among classes in an object-oriented system, showing the attributes, methods, and associations between them.

Logical Model A high-level structure and technical map for a database that specifies primary and foreign keys and has been normalized. 
Normalization The process of applying design rules to a database to ensure that its table structures minimize duplication and ensure efficiency and integrity.

Variety The different types and formats of data and big data.

Velocity The speed of data generation and the need to process and analyze data in real time. 
Volume The enormous amount of data generated and collected. 

Concurrency The ability for multiple users or processes to access and change a file at the same time.

Vendor Lock-In A situation in which a customer or organization becomes heavily dependent on a particular vendor's products, services, or technologies to the extent that it becomes difficult or costly to switch to an alternative vendor.

Universally Unique ID (UUID) A 128-bit identifier that is guaranteed to be unique across both space and time. It is often used as a primary key or unique identifier for records in a database, particularly in distributed and decentralized systems where ensuring uniqueness is crucial.
Common Table Expressions (CTEs) A feature introduced in ANSI SQL that allows temporary result sets for complex queries.

Business Rule Specific constraints and requirements that govern how data should be stored, processed, and managed in a database.

Referential Integrity Rules ensuring that data relationships remain valid and consistent. 
Decision Support System (DSS) A computer-based tool that helps individuals and organizations make informed decisions by providing access to data, analysis, and interactive tools to support the decision-making process.

Memory Bottleneck Occurs when the database system either does not have enough physical memory allocated for its use or is unable to access or manage memory resources effectively. 
Memory Leak A situation where a program allocates memory but then fails to release it when the memory is no longer needed. 
Query Optimizer A software that determines the most efficient way to execute a query.

Input/Output (IO) Bottleneck Occurs when there is a bandwidth limitation in reading from or writing to the storage device. 
Latency A delay between when a request is issued and its fulfillment. 
Fragmentation A condition in which a file is not stored contiguously on the disk, so the read/write head has to move around, picking up the pieces of the file when it is requested.
Isolation Level The degree to which one transaction must be isolated from the effects of other concurrent transactions. 
Database Locking A mechanism for controlling access to a database in a multiuser environment.
Disk Caching A way to improve performance by reducing the need to access physical storage for frequently accessed data. 
In-Memory Databases Databases that rely primarily on memory for data storage and retrieval.

Sharding A database architecture strategy that breaks up a large database into smaller, more manageable parts called shards. 
Connection Pooling A technique for managing and reusing database connections.

Indexing Bottleneck Occurs when the process of maintaining and updating indexes becomes a performance bottleneck.

Data Migration The process of transferring data from one database to another while ensuring the data's integrity, accuracy, and consistency. 
Validation Rule A constraint that prevents invalid, inaccurate, or inconsistent data from being populated into database entities.

Principle of Least Privilege A security strategy that gives users only the minimum privileges they need to do their work.
Multifactor Authentication (MFA) The practice of requiring two different forms of authentication for access to a system, such as a username/password and a PIN or access code. 
Data Masking A method of anonymization that replaces sensitive data with consistent, nonsensitive values.

