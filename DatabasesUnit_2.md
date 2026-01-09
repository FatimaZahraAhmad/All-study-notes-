# Databases Unit 2

## Entity Relationships

### Entity Types

**Strong Entity** - An entity that can exist independently of the other entities with which it has relationships.

**Weak Entity** - An entity that cannot exist independently of one or more other entities with which it has relationships.

**Associative Entity** - An entity that exists in order to normalize a many-to-many relationship between two other entities, converting it into one-to-many relationships to normalize the database.

### Relationship Types

**Direct Relationship** - A relationship that does not require an associative table—in other words, a one-to-one or one-to-many relationship.

**Strong Relationship** - A relationship between two strong entities (existentially independent of one another).

**Weak Relationship** - A relationship involving two entities whose existence is dependent on that of the related entity, or a relationship between a strong entity and a weak entity.

### Keys and Attributes

**Composite Key** - A key that consists of two or more attributes, the combination of which uniquely identifies a record.

**Attribute** - A characteristic or property of an entity that is stored in the database. Each column in a database table represents an attribute.

## Cardinality and Relationships

### Cardinality Types

**Cardinality** - The description of the numerical relationships between two tables.

**One-to-One (1:1)** - A relationship in which a single row in one table is related to just one row in another table and vice versa.

**One-to-Many (1:N)** - A relationship in which one row in a database table relates to many rows in a second table.

**Many-to-Many (M:N)** - A relationship in which many rows in one table are related to many rows in a second table. This relationship type isn't one that can be implemented in a relational model.

## Data Modeling Notations

### Chen Notation

**Chen Notation** - A visual representation technique for entity-relationship modeling that uses:
- Rectangles to represent entities
- Diamonds for relationships
- Lines to represent cardinality and participation constraints

### Other Notation Systems

**Crow's Foot Notation** - A graphical representation technique that uses various symbols to represent cardinality, relationships, attributes, and relationships between entities, such as crow's feet, lines, and diamonds.

**UML Class Diagram Notation** - A notation system that illustrates the structure and relationships among classes in an object-oriented system, showing the attributes, methods, and associations between them.

## Database Design Concepts

### Entity Identification

**Strong Entity** - An entity that can be uniquely identified by its own attributes alone.

**Weak Entity** - An entity that cannot be uniquely identified by only its own attributes.

### Relationship Strength

**Strong Relationship** - A relationship between two strong entities.

**Weak Relationship** - A relationship between a strong entity and a weak entity.