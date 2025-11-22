Databases 2



Asssociative Entity An entity that exists in order to normalize a many-to-many relationship between two other entities.

Composite Key A key that consists of two or more attributes, the combination of which uniquely identifies a record.
Chen Notation A visual representation technique for entity-relationship modeling that uses rectangles to represent entities, diamonds for relationships, and lines to represent cardinality and participation constraints.
Direct Relationship A relationship that does not require an associative table—in other words, a one-to-one or one-to-many relationship.
Strong Entity An entity that can exist independently of the other entities with which it has relationships.
Strong Relationship A relationship between two entities that are existentially independent of one another.
Weak Entity An entity that cannot exist independently of one or more other entities with which it has relationships.
Weak Relationship A relationship involving two entities whose existence is dependent on that of the related entity


Attribute A characteristic or property of an entity that is stored in the database. Each column in a database table represents an attribute.

Cardinality The description of the numerical relationships between two tables.
the cardinality items are; One-to-One (1:1) A relationship in which a single row in one table is related to just one row in another table and vice versa.
One-to-Many (1:N) A relationship in which one row in a database table relates to many rows in a second table. 
Many-to-Many (M:N) A relationship in which many rows in one table are related to many rows in a second table. This relationship type isn’t one that can be implemented in a relational model. 

Strong Relationship A relationship between two strong entities. 
Weak Relationship A relationship between a strong entity and a weak entity. 
Strong Entity An entity that can be uniquely identified by its own attributes alone.
Weak Entity An entity that cannot be uniquely identified by only its own attributes.

Associative Entity An entity that exists to convert a many-to-many relationship into one-to-many relationship to normalize the database.


Composite Key A key that uniquely identifies rows, or gives columns IDs, i.e the composite key of productid and orderid gives the id to the products and orders.
A key that uniquely identifies rows, or gives columns IDs, 
i.e the composite key of productid and orderid gives the id to the products and orders. 

Lookup Table A type of reference table that exists to provide a list of allowable values to populate an attribute in another table. 
Reference Table
A table that contains a series of key-value entries where the key attribute is the primary key and the value attribute is what the key represents.

Chen notation
A visual representation technique for entity-relationship modeling that uses rectangles to represent entities, diamonds for relationships, and lines to represent cardinality and ;participation constraints.

Crow's Foot Notation
A visual representation technique for entity-relationship modeling using crows feet for many or one cardinality and stores the attributes inside the boxes used for entities.

Normalization Normalization is the process of organizing and structuring data in a relational database efficiently,

Normal forms are sets of rules applied to a database design. The three most basic and most often used are:

first normal form (1NF),
rule: must be a proper table, no repeating groups or multiple values in a single cell.

second normal form (2NF), 
rule: should be in 1NF, then, ensure every column that isn't the primary key depends on all of the key, not just part of it.

third normal form (3NF),
rule: should be in 2NF, then, ensure that no column depends on another non-key column, all the non-key column must depend only on the primary key.

Boyce-Codd Normal Form The Boyce-Codd normal form, also known as BCNF, is viewed as 3.5NF. BCNF requires that the database design first fulfills the requirements of the third normal form (3NF) but also has every determinant in a table as a candidate key.

Fourth Normal Form (4NF) A database design that satisfies all of the properties of the third normal form (3NF) and Boyce-Codd normal form (BCNF), and additionally should not have any multivalued dependencies.

Fifth Normal Form (5NF) The fifth normal form (5NF) is mostly conceptual. A relation between tables is in 5NF if it is in the fourth
normal form (4NF) and contains no join dependencies.




Repeating Group A condition where an attribute contains multiple entries for a single record.

Functional Dependency A situation in which the primary key should determine each column in a table that is not a primary key

Determinants
groups of attributes that determine another attribute uniquely.

Candidate Key A set of one or more attributes that can uniquely identify each entry in a table. 
Alternate Key A candidate key that has not been selected as the primary key or part of the composite key

Denormalization A process that intentionally duplicates data or reintroduces redundancy to increase query performance, simplify data retrieval, and optimize certain operations.

Analytical Database A database that is used primarily to generate reports based on data that doesn't frequently change. It is optimized for fast querying. 
Transactional Database A database that is used primarily to accept and store new transactions. It is optimized for fast data input. 
Data Warehouse A centralized data repository collected from various sources, optimized for analysis, reporting, and decision making.

Cartesian Product An over-counting of data in a query that computes aggregates or counts when the query includes data from multiple tables that are not directly connected.
Chasm Trap A condition in which two one-to-many joins converge on a single table.
Connection Trap A situation where a complex relationship pattern can lead to ambiguous or incorrect query results and challenges in maintaining data integrity.
Dimension Table A table that supports a fact table by storing additional details about its data.
Fact Table A table that contains quantitative data such as sales figures or other measurable metrics.

Fan Trap 
A condition in which two one-to-many relationships follow one another in a parent-child form.

Snowflake Schema
A schema in which some of the dimension tables in a star schema have their own subordinate dimension tables.
Star Schema A schema in which a organizes data with a central fact table holding numerical data connected to tables with descriptive details, making it fast for analyzing and querying large datasets.



Business Process A set of activities or tasks that are performed in a coordinated manner to achieve a specific business goal. 
Business Use Case A detailed description of how a system will be used to achieve a specific business goal in a certain scenario.


