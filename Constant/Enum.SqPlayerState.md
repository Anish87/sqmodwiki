# Introduction

Identifies a certain player state.

# Specifications

```D
enum SqPlayerState
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **None** | `integer` | The player in the default state |
| **Normal** | `integer` | The player in the normal state |
| **Aim** | `integer` | The player in the aiming state |
| **Driver** | `integer` | The player in the driver state |
| **Passenger** | `integer` | The player in the passenger state |
| **EnterDriver** | `integer` | The player in the embarking as driver state |
| **EnterPassenger** | `integer` | The player in the embarking as passenger state |
| **Exit** | `integer` | The player in the disembarking state |
| **Unspawned** | `integer` | The player in the unspawned state |
| **Max** | `integer` | Maximum identifier in this enumeration |
