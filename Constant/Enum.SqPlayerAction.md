# Introduction

Identifies a certain player action.

# Specifications

```D
enum SqPlayerAction
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **None** | `integer` | The player is performing no action |
| **Normal** | `integer` | The player is performing a normal action |
| **Aiming** | `integer` | The player is performing an aiming action |
| **Shooting** | `integer` | The player is performing a shooting action |
| **Jumping** | `integer` | The player is performing a jumping action |
| **LyingOnGround** | `integer` | The player is performing a lie down action |
| **GettingUp** | `integer` | The player is performing a getting up action |
| **JumpingFromVehicle** | `integer` | The player is performing a vehicle jump action |
| **Driving** | `integer` | The player is performing a driving action |
| **Dying** | `integer` | The player is performing a dying action |
| **Wasted** | `integer` | The player is performing a wasted action |
| **EnteringVehicle** | `integer` | The player is performing an embarking action |
| **ExitingVehicle** | `integer` | The player is performing a disembarking action |
| **Max** | `integer` | Maximum identifier in this enumeration |
