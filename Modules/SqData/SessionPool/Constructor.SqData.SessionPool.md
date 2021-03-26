# SqData.SessionPool

## constructor

```squirrel
SqData.SessionPool(string Type [, integer Min] [, integer Max] [, integer Idle], string ConnectionString)
```

## Parameters

* *string* **Type:** Type of the session.
* *optional integer* **Min:** Minimum number of sessions (default is 1).
* *optional integer* **Max:** Maximum number of sessions (default is 32).
* *optional integer* **Idle:** Idle time for the session (default is 60).
* *string* **ConnectionString:** Refer [here](https://github.com/VCMP-SqMod/SqMod/blob/d853e86d189c18c5d2f5b4ccacc5a54d581efcea/vendor/POCO/Data/MySQL/include/Poco/Data/MySQL/SessionImpl.h#L45).

## Example

```squirrel
// Default values:
// Min Sessions: 1
// Max Sessions: 32
// Idle Time: 60
Pool <- SqData.SessionPool("sqlite", ":memory:");

// Explicit values
// Pool <- SqData.SessionPool("sqlite", 1, 32, 60, ":memory:");

/// And then the usual
SqData.Statement(Pool.Get(), "CREATE TABLE ...")
SqData.Statement(Pool.Get(), "INSERT INTO ...")
SqData.Statement(Pool.Get(), "SELECT * FROM ...")
```