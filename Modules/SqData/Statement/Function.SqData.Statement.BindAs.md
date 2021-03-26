# Description

Alias to [Bind](Function.SqData.Statement.Bind), but for named values instead.

## Usage

Consider this example with `Bind`
```squirrel
local First = 1, Second = 2;

SqData.Statement(DB, "INSERT INTO test VALUES (?, ?)")
    .Bind(First)
    .Bind(Second)
    .Execute();
```

The same can be achieved via `BindAs` if you want to ditch `?`
```squirrel
local First = 1, Second = 2;

SqData.Statement(DB, "INSERT INTO test VALUES (:first, :second)")
    .BindAs(Second, "second")
    .BindAs(First, "first")
    .Execute();
```