# Introduction

Identifies the world weather.

# Specifications

```D
enum SqWeather
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **MostlyClear** | `integer` | The weather is: *mostly clear*
| **Overcast** | `integer` | The weather is: *overcast*
| **ThunderStorm** | `integer` | The weather is: *thunder storm*
| **Storm** | `integer` | The weather is: *storm*
| **Stormy** | `integer` | The weather is: *stormy*
| **Foggy** | `integer` | The weather is: *foggy*
| **Fog** | `integer` | The weather is: *fog*
| **Clear** | `integer` | The weather is: *clear*
| **Sunny** | `integer` | The weather is: *sunny*
| **Rain** | `integer` | The weather is: *rain*
| **Rainy** | `integer` | The weather is: *rainy*
| **DarkCloudy** | `integer` | The weather is: *dark cloudy*
| **LightCloudy** | `integer` | The weather is: *light cloudy*
| **OvercastCloudy** | `integer` | The weather is: *overcast cloudy*
| **BlackClouds** | `integer` | The weather is: *black clouds*
| **Max** | `integer` | Maximum identifier in this enumeration |
