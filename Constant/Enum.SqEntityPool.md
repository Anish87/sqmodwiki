# Introduction

Specifies which entity pool was updated.

# Specifications

```D
enum SqEntityPool
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown change occurred. Never really used but added for consistency |
| **Vehicle** | `integer` | The update occurred in the vehicle pool |
| **Object** | `integer` | The update occurred in the object pool |
| **Pickup** | `integer` | The update occurred in the pickup pool |
| **Radio** | `integer` | The update occurred in the radio pool |
| **Blip** | `integer` | The update occurred in the blip pool |
| **Checkpoint** | `integer` | The update occurred in the checkpoint pool |
| **Max** | `integer` | Maximum identifier in this enumeration |
