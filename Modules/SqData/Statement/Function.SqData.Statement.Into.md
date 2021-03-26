# Description

It is used to register a single extraction with the statement.

## Function

```squirrel
.Into(SqData.Binding Bind [, Default])
```

## Paremeters

* *SqData.Binding* **Bind:** The binding to extract the value into.
* *optional* **Default:** Default value for the bind.

## Example

```squirrel
local Name = SqData.StrBind();

local Query = SqData.Statement(DB, "SELECT Name FROM accounts WHERE ID = 1").Into(Name).Execute();
if(Query == 1) SqLog.Inf("Name at ID 1 is: " + Name.Value);
```