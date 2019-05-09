# Introduction

Several sample reasons why an entity is being created. These identifiers will be in the header parameter if the plug-in created that entity automatically or the user specified them manually. Otherwise they won't be used. The values in these enumeration elements will always be negative to allow the distinction between player identifiers and plug-in identifiers.

# Specifications

```D
enum SqCreate
```

----

| Name | Type | Description |
|---|---|---|
| **Default** | `integer` | Default value when no header was specified |
| **Manual** | `integer` | Can be used when a user creates the entity manually |
| **Pool** | `integer` | Will be used the entity was created in the server pool automatically |
| **Automatic** | `integer` | Will be used when the entity is created automatically for some reason |
| **Overwrite** | `integer` | Can be used to specify that this entity is meant to overwrite another |
| **Import** | `integer` | Will be used when the plug-in imports existing entities after the scripts are loaded |
