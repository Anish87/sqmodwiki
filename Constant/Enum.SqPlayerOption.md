# Introduction

Identifies player options that can be modified.

# Specifications

```D
enum SqPlayerOption
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **Controllable** | `integer` | Allow the player to be controlled |
| **DriveBy** | `integer` | Enable driveby |
| **WhiteScanlines** | `integer` | Enable white scanlines |
| **GreenScanlines** | `integer` | Enable green scanlines |
| **Widescreen** | `integer` | Enable wide screen |
| **ShowMarkers** | `integer` | Allow the player to see markers |
| **CanAttack** | `integer` | Allow the player to inflict damage on other players |
| **HasMarker** | `integer` | Enable player marker |
| **ChatTagsEnabled** | `integer` | Enable chat tags |
| **DrunkEffects** | `integer` | Enable drunk effects on the player |
| **Max** | `integer` | Maximum identifier in this enumeration |
