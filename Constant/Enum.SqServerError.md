# Introduction

Identifies types of errors occurred in the server.

# Specifications

```D
enum SqServerError
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **None** | `integer` | No error occurred |
| **NoSuchEntity** | `integer` | The accessed entity does not exist |
| **BufferTooSmall** | `integer` | The given buffer was too small for the requested data |
| **TooLargeInput** | `integer` | The value input was too large |
| **ArgumentOutOfBounds** | `integer` | The given argument or identifier is out of range |
| **NullArgument** | `integer` | The given argument is null |
| **PoolExhausted** | `integer` | Cannot create any more entities of a certain type |
| **InvalidName** | `integer` | The specified player name is invalid |
| **RequestDenied** | `integer` | The player was denied access in the vehicle |
| **Max** | `integer` | Maximum identifier in this enumeration |
