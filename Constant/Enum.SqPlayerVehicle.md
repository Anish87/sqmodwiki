# Introduction

Identifies the player state in regards to vehicles.

# Specifications

```D
enum SqPlayerVehicle
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **Out** | `integer` | Out of vehicle |
| **Entering** | `integer` | Entering a vehicle |
| **Exiting** | `integer` | Exiting a vehicle |
| **In** | `integer` | Inside a vehicle |
| **Max** | `integer` | Maximum identifier in this enumeration |
