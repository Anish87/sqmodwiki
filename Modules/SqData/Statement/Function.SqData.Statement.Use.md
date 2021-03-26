# Description

This can be used to bind references to a statement.

## Examples

```squirrel
DB <- SqData.Session("sqlite", ":memory:", 60);

SqData.Statement(DB, "CREATE TABLE test (First NUMBER(3), Second NUMBER(3))").Execute(); 

local   First   = SqData.IntBind(),
        Second  = SqData.IntBind();

local   Query   = SqData.Statement(DB, "INSERT INTO test VALUES (?, ?)").Use(First).Use(Second);

First.Value = 5; Second.Value = 10;
Query.Execute();

First.Value = 10; Second.Value = 5;
Query.Execute();
```

## Notes

* Use is **only** used for references.
* Refer to [Bind](Function.SqData.Statement.Bind) for fundamental values.