# Description

Executes the statement asynchronously without changing its synchronous nature.

> Synchronous nature of a statement can be changed using the [SetAsync](Function.SqData.Statement.SetAsync) function. Once set as `asynchronous`, it's always executed asynchronously until its set back to synchronous by either `Reset` or `SetAsync` functions.

## Function

```squirrel
.ExecuteAsync(bool Reset = true)
```

## Parameters

* *bool* **Reset:** Whether to reset and reuse associated storage (default is true).

## Usage

```squirrel
SqData.Statement(...).ExecuteAsync().Bind(function(stmt, result) {
    // Statement `stmt` completed execution and returned `result`
});
```

Asynchronous calls require:

```squirrel
// Call SqData.Process every 1ms (i.e every frame) and wait 1ms for each result to respond
SqRoutine(this, SqData.Process, 1, 0, 1);
```