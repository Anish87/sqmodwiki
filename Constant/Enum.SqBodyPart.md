# Introduction

Identifies a character body part. Mostly used to identify where the final blow occurred when a player was killed.

# Specifications

```D
enum SqBodyPart
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **Body** | `integer` | The character body |
| **Torso** | `integer` | The character torso |
| **LeftArm** | `integer` | The character left arm |
| **RightArm** | `integer` | The character right arm |
| **LeftLeg** | `integer` | The character left leg |
| **RightLeg** | `integer` | The character right leg |
| **Head** | `integer` | The character head |
| **LArm** | `integer` | Alias of ''LeftArm'' |
| **RArm** | `integer` | Alias of ''RightArm'' |
| **LLeg** | `integer` | Alias of ''LeftLeg'' |
| **RLeg** | `integer` | Alias of ''RightLeg'' |
| **InVehicle** | `integer` | The character is inside a vehicle |
| **Max** | `integer` | Maximum identifier in this enumeration |
