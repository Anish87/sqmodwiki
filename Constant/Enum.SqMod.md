# Introduction

A set of values that are required by some of the underlying code and could change depending on the compiler, architecture or even after changes to the plugin. They're only made available to avoid hard-coded values in production code. Some of them are necessary while some of them are almost optional for most people. But they're exported simply to expose as much as possible of the underlying implementation.

----

```D
enum SqMod
```

----

| Name | Type | Description |
|---|---|---|
| **Version** | `integer` | Plug-in version |
| **Success** | `integer` | Success value. Possible value is `1` |
| **Failure** | `integer` | Failure value. Possible value is `0` |
| **Unknown** | `integer` | Unknown value. Possible value is `-1` |
| **Arch** | `integer` | Alias of `Architecture` |
| **Architecture** | `integer` | Architecture identifier. See [SqArchitecture](Enum.SqArchitecture) |
| **Platform** | `integer` | Platform identifier. See [SqPlatform](Enum.SqPlatform) |
| **MinChar** | `integer` | Minimum value of a Squirrel character. Same as 8 bit ASCII characters. |
| **MaxChar** | `integer` | Maximum value of a Squirrel character. Same as 8 bit ASCII characters. |
| **MinAchar** | `integer` | Minimum value of an 8 bit signed integer. Possible value is `-128` |
| **MaxAchar** | `integer` | Maximum value of an 8 bit signed integer. Possible value is `127` |
| **MinByte** | `integer` | Minimum value of an 8 bit unsigned integer. Possible value is `0` |
| **MaxByte** | `integer` | Maximum value of an 8 bit unsigned integer. Possible value is `255` |
| **MinShort** | `integer` | Minimum value of an 16 bit signed integer. Possible value is `-32768` |
| **MaxShort** | `integer` | Maximum value of an 16 bit signed integer. Possible value is `32767` |
| **MinWord** | `integer` | Minimum value of an 16 bit unsigned integer. Possible value is `0` |
| **MaxWord** | `integer` | Maximum value of an 16 bit unsigned integer. Possible value is `65535` |
| **MinInt** | `integer` | Alias of `MinInteger` |
| **MaxInt** | `integer` | Alias of `MaxInteger` |
| **MinInteger** | `integer` | Minimum value of a Squirrel integer. Possible value is `-2147483648` on 32-bit or ` -9223372036854775808` on 64-bit. |
| **MaxInteger** | `integer` | Maximum value of a Squirrel integer. Possible value is `2147483647` on 32-bit or `9223372036854775807` on 64-bit. |
| **MinInt32** | `integer` | Minimum value of an 32 bit signed integer. Possible value is `-2147483648` |
| **MaxInt32** | `integer` | Maximum value of an 32 bit signed integer. Possible value is `2147483647` |
| **MinFloat** | `float` | Minimum value of a Squirrel floating point number. |
| **MaxFloat** | `float` | Minimum value of a Squirrel floating point number. |
| **MinFloat32** | `float` | Minimum value of a 32-bit floating point number. |
| **MaxFloat32** | `float` | Minimum value of a 32-bit floating point number. |
| **FpNormal** | `float` | Indicates that the value is normal, i.e. not an infinity, subnormal, not-a-number or zero |
| **FpSubnormal** | `float` | Indicates that the value is subnormal |
| **FpZero** | `float` | Indicates that the value is positive or negative zero |
| **FpInfinite** | `float` | Indicates that the value is not representable by the underlying type (positive or negative infinity) |
| **FpNan** | `float` | Indicates that the value is not-a-number (NaN) |
| **HugeVal** | `float` | Indicates floating point overflow |
| **Infinity** | `float` | A positive value that is guaranteed to overflow a floating point number |
| **Inf** | `float` | Alias of `Infinity` |
| **Nan** | `float` | Quiet NaN of type `float` |
| **MaxTasks** | `integer` | Maximum number of tasks that can be active.
| **MaxRoutines** | `integer` | Maximum number of routines that can be active.
