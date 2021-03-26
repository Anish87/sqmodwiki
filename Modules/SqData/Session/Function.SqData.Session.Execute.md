# Description

Executes the statement.

Statement is executed asynchronously if its set to be async using the [SetAsync](Function.SqData.Statement.SetAsync) function. However you can not bind it to a function, its recommend to use [ExecuteAsync](Function.SqData.Statement.ExecuteAsync).

## Function

```squirrel
.Execute(bool Reset = true)
```

## Parameters

* *bool* **Reset:** Whether to reset and reuse associated storage (default is true).

## Returns

* **Synchronous:** The statement will return the number of rows affected.
* **Asynchronous:** Zero (0).