# Introduction

Specifies what kind of update occurred on a vehicle.

# Specifications

```D
enum SqVehicleUpdate
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **DriverSync** | `integer` | Driver synchronization |
| **OtherSync** | `integer` | Miscellaneous synchronization |
| **Position** | `integer` | Position changed |
| **Health** | `integer` | Health changed |
| **Color** | `integer` | Color changed |
| **Colour** | `integer` | Alias of ''Color'' |
| **Rotation** | `integer` | Rotation changed |
| **Max** | `integer` | Maximum identifier in this enumeration |
