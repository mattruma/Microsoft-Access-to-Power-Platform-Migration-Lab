# Make Table

This table manages all the available makes that can be associated with a car, e.g., `Ford` or `Honda`.

**Primary Key(s)**: make_id

## Fields

List of fields in the table.

```mermaid
erDiagram
    Make {
        int make_id
        string name
    }

```

### make_id

**Type**: Long Integer, AutoNumber

**Description**: The unique identifier of the record

### name

**Type**: Short Text

**Size**: 255

**Description**: The name of the make, e.g., `Ford` or `Honda`

## Relationships

The relationships between tables in the database, that includes this table.

[Make Table Car Table](Database-Table-Relationships.md)
