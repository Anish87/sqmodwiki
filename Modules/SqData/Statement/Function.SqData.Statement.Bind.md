# Description

This can be used to bind values to a statement.

## Examples

```squirrel
DB <- SqData.Session("sqlite", ":memory:", 60);

SqData.Statement(DB, "CREATE TABLE test (First NUMBER(3), Second NUMBER(3))").Execute(); 

local   First   = 1,
        Second  = 2;

SqData.Statement(DB, "INSERT INTO test VALUES (?, ?)")
    .Bind(First)
    .Bind(Second)
    .Execute();
```