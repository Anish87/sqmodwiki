# Introduction

Specifies what kind of update occurred on a player.

# Specifications

```D
enum SqPlayerUpdate
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **Normal** | `integer` | The player is doing nothing |
| **Aiming** | `integer` | The player is aiming |
| **Driver** | `integer` | The player is driving |
| **Passenger** | `integer` | The player is a passenger |
| **Max** | `integer` | Maximum identifier in this enumeration |
