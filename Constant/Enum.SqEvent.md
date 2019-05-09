# Introduction

Used to identify the available server events to which you can bind.

# Specifications

```D
enum SqEvent
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown event |
| **CustomEvent** | `integer` | Custom event |
| **BlipCreated** | `integer` | An ''SqBlib'' instance was created |
| **CheckpointCreated** | `integer` | An [SqCheckpoint](Class.SqCheckpoint) instance was created |
| **KeybindCreated** | `integer` | An [SqKeybind](Class.SqKeybind) instance was created |
| **ObjectCreated** | `integer` | An [SqObject](Class.SqObject) instance was created |
| **PickupCreated** | `integer` | An [SqPickup](Class.SqPickup) instance was created |
| **PlayerCreated** | `integer` | An [SqPlayer](Class.SqPlayer) instance was created |
| **VehicleCreated** | `integer` | An [SqVehicle](Class.SqVehicle) instance was created |
| **BlipDestroyed** | `integer` | An [SqBlib](Class.SqBlib) instance was destroyed |
| **CheckpointDestroyed** | `integer` | An [SqCheckpoint](Class.SqCheckpoint) instance was destroyed |
| **KeybindDestroyed** | `integer` | An [SqKeybind](Class.SqKeybind) instance was destroyed |
| **ObjectDestroyed** | `integer` | An [SqObject](Class.SqObject) instance was destroyed |
| **PickupDestroyed** | `integer` | An [SqPickup](Class.SqPickup) instance was destroyed |
| **PlayerDestroyed** | `integer` | An [SqPlayer](Class.SqPlayer) instance was destroyed |
| **VehicleDestroyed** | `integer` | An [SqVehicle](Class.SqVehicle) instance was destroyed |
| **BlipCustom** | `integer` | An [SqBlib](Class.SqBlib) instance sent a custom event |
| **CheckpointCustom** | `integer` | An [SqCheckpoint](Class.SqCheckpoint) instance sent a custom event |
| **KeybindCustom** | `integer` | An [SqKeybind](Class.SqKeybind) instance sent a custom event |
| **ObjectCustom** | `integer` | An [SqObject](Class.SqObject) instance sent a custom event |
| **PickupCustom** | `integer` | An [SqPickup](Class.SqPickup) instance sent a custom event |
| **PlayerCustom** | `integer` | An [SqPlayer](Class.SqPlayer) instance sent a custom event |
| **VehicleCustom** | `integer` | An [SqVehicle](Class.SqVehicle) instance sent a custom event |
| **ServerStartup** | `integer` | The server is starting up |
| **ServerShutdown** | `integer` | The server is shutting down |
| **ServerFrame** | `integer` | The server completed a frame |
| **IncomingConnection** | `integer` | There's an incoming client connection |
| **PlayerRequestClass** | `integer` | A player requests to use a class |
| **PlayerRequestSpawn** | `integer` | A player requests to spawn |
| **PlayerSpawn** | `integer` | A player has spawned |
| **PlayerWasted** | `integer` | A player died |
| **PlayerKilled** | `integer` | A player was killed |
| **PlayerEmbarking** | `integer` | A player requests to enter a vehicle |
| **PlayerEmbarked** | `integer` | A player entered a vehicle |
| **PlayerDisembark** | `integer` | A player exited a vehicle |
| **PlayerRename** | `integer` | A player changed his name |
| **PlayerState** | `integer` | A player entered a different state |
| **StateNone** | `integer` | A player is currently in the default state |
| **StateNormal** | `integer` | A player is currently in the normal state |
| **StateAim** | `integer` | A player is currently in the aiming state |
| **StateDriver** | `integer` | A player is currently in the driver state |
| **StatePassenger** | `integer` | A player is currently in the passenger state |
| **StateEnterDriver** | `integer` | A player is currently in the embarking as driver state |
| **StateEnterPassenger** | `integer` | A player is currently in the embarking as passenger state |
| **StateExit** | `integer` | A player is currently in the disembarking state |
| **StateUnspawned** | `integer` | A player is currently in the un-spawned state |
| **PlayerAction** | `integer` | A player is performing a different action |
| **ActionNone** | `integer` | A player is currently performing no action |
| **ActionNormal** | `integer` | A player is currently performing a normal action |
| **ActionAiming** | `integer` | A player is currently performing an aiming action |
| **ActionShooting** | `integer` | A player is currently performing a shooting action |
| **ActionJumping** | `integer` | A player is currently performing a jumping action |
| **ActionLieDown** | `integer` | A player is currently performing a lie down action |
| **ActionGettingUp** | `integer` | A player is currently performing a getting up action |
| **ActionJumpVehicle** | `integer` | A player is currently performing a vehicle jump action |
| **ActionDriving** | `integer` | A player is currently performing a driving action |
| **ActionDying** | `integer` | A player is currently performing a dying action |
| **ActionWasted** | `integer` | A player is currently performing a wasted action |
| **ActionEmbarking** | `integer` | A player is currently performing an embarking action |
| **ActionDisembarking** | `integer` | A player is currently performing a disembarking action |
| **PlayerBurning** | `integer` | A player is currently burning or stopped burning |
| **PlayerCrouching** | `integer` | A player is currently crouching or stopped crouching |
| **PlayerGameKeys** | `integer` | A player is pressing game keys |
| **PlayerStartTyping** | `integer` | A player started typing in the console |
| **PlayerStopTyping** | `integer` | A player stopped typing in the console |
| **PlayerAway** | `integer` | A player is currently marked as a way or active |
| **PlayerMessage** | `integer` | A player sent a chat message |
| **PlayerCommand** | `integer` | A player sent a command message |
| **PlayerPrivateMessage** | `integer` | A player sent a private message |
| **PlayerKeyPress** | `integer` | A player activated a press key-bind |
| **PlayerKeyRelease** | `integer` | A player activated a release key-bind |
| **PlayerSpectate** | `integer` | A player started spectating another player |
| **PlayerUnspectate** | `integer` | A player stopped spectating another player |
| **PlayerCrashReport** | `integer` | A player sent a crash report | 
| **PlayerModuleList** | `integer` | The server requested a list if modules loaded in the client |
| **VehicleExplode** | `integer` | A vehicle exploded |
| **VehicleRespawn** | `integer` | A vehicle was re-spawned |
| **ObjectShot** | `integer` | An object was shot by a player |
| **ObjectTouched** | `integer` | An object was touched by a player |
| **ObjectWorld** | `integer` | An object world was changed |
| **ObjectAlpha** | `integer` | An object alpha was changed |
| **ObjectReport** | `integer` | An object report status was changed |
| **PickupClaimed** | `integer` | A player claimed ownership of a pickup |
| **PickupCollected** | `integer` | A player collected a pickup |
| **PickupRespawn** | `integer` | A pickup was re-spawned |
| **PickupWorld** | `integer` | A pickup world was changed |
| **PickupAlpha** | `integer` | A pickup alpha was changed |
| **PickupAutomatic** | `integer` | A pickup auto status was changed |
| **PickupAutoTimer** | `integer` | A pickup auto timer was changed |
| **PickupOption** | `integer` | A pickup option was changed |
| **CheckpointEntered** | `integer` | A player entered a checkpoint |
| **CheckpointExited** | `integer` | A player exited a checkpoint |
| **CheckpointWorld** | `integer` | A checkpoint world was changed |
| **CheckpointRadius** | `integer` | A checkpoint radius was changed |
| **EntityPool** | `integer` | A change occurred in the entity pool |
| **ClientScriptData** | `integer` | A client sent custom data to the server |
| **PlayerUpdate** | `integer` | A change occurred in a player |
| **VehicleUpdate** | `integer` | A change occurred in a vehicle |
| **PlayerHealth** | `integer` | A player health changed |
| **PlayerArmour** | `integer` | A player armor changed |
| **PlayerWeapon** | `integer` | A player weapon changed |
| **PlayerHeading** | `integer` | A player heading changed |
| **PlayerPosition** | `integer` | A player position changed |
| **PlayerOption** | `integer` | A player option changed |
| **PlayerAdmin** | `integer` | A player administrator status was changed |
| **PlayerWorld** | `integer` | A player world was changed |
| **PlayerTeam** | `integer` | A player team was changed |
| **PlayerSkin** | `integer` | A player skin was changed |
| **PlayerMoney** | `integer` | A player money was changed |
| **PlayerScore** | `integer` | A player score was changed |
| **PlayerWantedLevel** | `integer` | A player wanted level was changed |
| **PlayerImmunity** | `integer` | A player immunity was changed |
| **PlayerAlpha** | `integer` | A player alpha was changed |
| **VehicleColor** | `integer` | A vehicle color changed |
| **VehicleColour** | `integer` | A vehicle color changed |
| **VehicleHealth** | `integer` | A vehicle health changed |
| **VehiclePosition** | `integer` | A vehicle position changed |
| **VehicleRotation** | `integer` | A vehicle rotation changed |
| **VehicleOption** | `integer` | A vehicle option was changed |
| **VehicleWorld** | `integer` | A vehicle world was changed |
| **VehicleImmunity** | `integer` | A vehicle immunity was changed |
| **VehiclePartStatus** | `integer` | A vehicle part status was changed |
| **VehicleTyreStatus** | `integer` | A vehicle tyre status was changed |
| **VehicleDamageData** | `integer` | A vehicle damage data was changed |
| **VehicleRadio** | `integer` | A vehicle radio was changed |
| **VehicleHandlingRule** | `integer` | A vehicle handling rule was changed |
| **ServerOption** | `integer` | A server option changed |
| **ScriptReload** | `integer` | A script reload was requested |
| **ScriptLoaded** | `integer` | All scripts were successfully executed |
| **Max** | `integer` | Maximum identifier for an event |
