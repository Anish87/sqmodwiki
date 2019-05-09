#  Welcome to the VCMP-SqMod wiki!

The **VC:MP Squirrel Module** is a plugin that can be loaded by the **VC:MP** server to provide a user the ability to script behavior into his server using the Squirrel scripting language. The goal of this plugin is to provide high-end features to the scripter and targets large scale game-mods. This is not an official module and __requires a significant amount of programming knowledge__ in ordered to be used properly.

----

## Constants

* `enum` [SqMod](Enum.SqMod)
* `enum` [SqArchitecture](Enum.SqArchitecture)
* `enum` [SqPlatform](Enum.SqPlatform)
* `enum` [SqEvent](Enum.SqEvent)
* `enum` [SqCreate](Enum.SqCreate)
* `enum` [SqDestroy](Enum.SqDestroy)
* `enum` [SqServerError](Enum.SqServerError)
* `enum` [SqEntityPool](Enum.SqEntityPool)
* `enum` [SqPlayerUpdate](Enum.SqPlayerUpdate)
* `enum` [SqVehicleUpdate](Enum.SqVehicleUpdate)
* `enum` [SqPlayerVehicle](Enum.SqPlayerVehicle)
* `enum` [SqVehicleSync](Enum.SqVehicleSync)
* `enum` [SqPartReason](Enum.SqPartReason)
* `enum` [SqServerOption](Enum.SqServerOption)
* `enum` [SqPlayerOption](Enum.SqPlayerOption)
* `enum` [SqVehicleOption](Enum.SqVehicleOption)
* `enum` [SqPickupOption](Enum.SqPickupOption)
* `enum` [SqBodyPart](Enum.SqBodyPart)
* `enum` [SqPlayerState](Enum.SqPlayerState)
* `enum` [SqPlayerAction](Enum.SqPlayerAction)
* `enum` [SqWeather](Enum.SqWeather)
* `enum` [SqWep](Enum.SqWep)
* `enum` [SqVeh](Enum.SqVeh)
* `enum` [SqSkin](Enum.SqSkin)
* `enum` [SqKeyCode](Enum.SqKeyCode)
* `enum` [SqASCII](Enum.SqASCII)

----

## Base Types

* `class` [AABB](Class.AABB)
* `class` [Circle](Class.Circle)
* `class` [Color3](Class.Color3)
* `class` [Color4](Class.Color4)
* `class` [Quaternion](Class.Quaternion)
* `class` [Sphere](Class.Sphere)
* `class` [Vector2](Class.Vector2)
* `class` [Vector2i](Class.Vector2i)
* `class` [Vector3](Class.Vector3)
* `class` [Vector4](Class.Vector4)

----

## Entity Types

* `class` [SqBlip](Class.SqBlip)
* `class` [SqCheckpoint](Class.SqCheckpoint)
* `class` [SqKeybind](Class.SqKeybind)
* `class` [SqObject](Class.SqObject)
* `class` [SqPickup](Class.SqPickup)
* `class` [SqPlayer](Class.SqPlayer)
* `class` [SqVehicle](Class.SqVehicle)

----

## Entity Algorithms

* `table` [SqCollect](Table.SqCollect)
* `table` [SqFind](Table.SqFind)
* `table` [SqForeach](Table.SqForeach)
* `table` [SqForeachEx](Table.SqForeachEx)
* `table` [SqCount](Table.SqCount)
