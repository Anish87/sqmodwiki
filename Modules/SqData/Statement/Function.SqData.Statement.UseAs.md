# Description

Alias to [Use](Function.SqData.Statement.Use), but for named references instead.

## Usage

Consider this example with `Use`
```squirrel
local   First   = SqData.IntBind(),
        Second  = SqData.IntBind();

SqData.Statement(DB, "INSERT INTO test VALUES (?, ?)")
    .Use(First)
    .Use(Second)
    .Execute();
```

The same can be achieved via `UseAs` if you want to ditch `?`
```squirrel
local   First   = SqData.IntBind(),
        Second  = SqData.IntBind();

SqData.Statement(DB, "INSERT INTO test VALUES (:first, :second)")
    .UseAs(Second, "second")
    .UseAs(First, "first")
    .Execute();
```