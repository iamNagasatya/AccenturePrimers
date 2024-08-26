# Alter, Truncate and Drop Statements

**Syntax**

```
ALTER TABLE TableName ADD
(
    ColumnName1 DataType [[CONSTRAINT ConstraintName1] ConstraintType],
    [[CONSTRAINT ConstraintName2] ConstraintType (Cname1 [, Cname2, ...])]
    ........................................................................
    ColumnNameN DataType [[CONSTRAINT ConstraintName1] ConstraintType],
);
```