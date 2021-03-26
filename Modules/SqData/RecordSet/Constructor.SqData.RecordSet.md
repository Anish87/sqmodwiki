# SqData.RecordSet

## constructor

```squirrel
SqData.RecordSet(SqData.Session Handler, string Query);
```

## Parameters

* *SqData.Session* **Handler:** Database handler.
* *string* **Query:** SQL Query.

## constructing from a statement

```squirrel
SqData.RecordSet(SqData.Statement Statement)
```

## Parameters
* *SqData.Statement* **Statement:** Alternatively, a record set can also be constructed using a SqData.Statement.

## Examples

Example #1 in [snippets](https://github.com/VCMP-SqMod/SqMod-Snippets/blob/b888ad51088e74e9ac07dc16f55b1501c0972729/SqData/hello.nut#L58).


Constructing from a statement: 
```squirrel
local Search = "%player%";
local Query = SqData.RecordSet(SqData.Statement(DB, "SELECT * FROM accounts WHERE Name LIKE ?").Bind(Search).Execute_());

for (local Iterator = Query.RowCount > 0 ; Iterator ; Iterator = Query.Next())
SqLog.Inf(format("Match found: %s", Query.Value("Name"));
```