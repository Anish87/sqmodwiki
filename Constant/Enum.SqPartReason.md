# Introduction

Specifies why a player disconnected from the server.

# Specifications

```D
enum SqPartReason
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **Timeout** | `integer` | The connection timed-out |
| **Quit** | `integer` | The player left the server |
| **Kick** | `integer` | The player was kicked or banned from the server |
| **Crash** | `integer` | The player client crashed |
| **AntiCheat** | `integer` | The player was caught by the anti-cheat system |
| **Max** | `integer` | Maximum identifier in this enumeration |
