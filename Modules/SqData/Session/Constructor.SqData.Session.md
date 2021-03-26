# SqData.Session

## constructor

```squirrel
SqData.Session(string Type, string ConnectionString, integer LoginTimeout)
```

## Parameters

* *string* **Type:** Type of the database (`sqlite`, `mysql` or `postgresql`).
* *string* **ConnectionString:** Refer [here](https://github.com/VCMP-SqMod/SqMod/blob/d853e86d189c18c5d2f5b4ccacc5a54d581efcea/vendor/POCO/Data/MySQL/include/Poco/Data/MySQL/SessionImpl.h#L45).
* *integer* **LoginTimeout:** Timeout for session login.

## Sqlite Example

```squirrel
SQLiteDB <- SqData.Session("sqlite", ":memory:", 60);
```

```squirrel
SQLiteDB <- SqData.Session("sqlite", "db/accounts.sqlite", 60);
```

## MySQL Example

```squirrel
local ConnectionString = "host=127.0.0.1;user=vcmp;port=3306;password=pass123;db=raceserver;auto-reconnect=true";
Database <- SqData.Session("mysql", ConnectionString, 60);
```

## PostgreSQL Example
```squirrel
local ConnectionString = "host=127.0.0.1;user=vcmp;port=3306;password=pass123;db=raceserver";
PGSQL <- SqData.Session("postgresql", ConnectionString, 60);
```