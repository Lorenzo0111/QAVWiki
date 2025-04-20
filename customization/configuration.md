---
description: Learn how to configure the plugin
---

# Configuration

The configuration documentation is structured in the following format:

Title: Setting\
Description: What the setting does

{% hint style="info" %}
If an option is not documented on this list, it is a deprecated or a no longer used option
{% endhint %}

### prefix

The prefix of the plugin. It is used in all messages.\
To disable it, just set it to "".

### USE\_1\_13\_MODEL\_SYSTEM

If set to true, the plugin will use a legacy method for handling vehicles.

### enable\_VehicleLimiter

If set to true, the plugin will limit per-player owned vehicles based on their permission.\
For example, if the player has the `qualityarmoryvehicles.vehiclelimit.5` permission, he will have a limit of 5 vehicles.

### enable\_PickupVehicles

If set to true, players will be able to pick up the vehicle from the gui.

### enable\_UnlockableVehicles

If set to true, when picking up a vehicle, it will be put in the player's garage.

### enable\_GarageCallback

If set to true, players will be able to pick up their spawned vehicles by clicking on it in the /garage gui.

### enable\_RequirePermsToDriveType

If set to true, players will have to have a permission to drive a vehicle.\
For example `qualityarmoryvehicles.candrive.ambulance`.

### enable\_SetOwnerOnVehicleSpawn

If set to true, when a vehicle is spawned, it will be automatically owned by the player who placed it.

### enable\_VehicleDamage

If set to true, players will be able to damage a vehicle with a gun or by hitting it.

### enable\_SetOwnerOfVehicleIfUnowned

If set to true, when a player enters a vehicle's driver seat, if no owner is set, he will become the vehicle's owner.

### Enable\_Creation\_Of\_Default\_Files

If set to true, the plugin will generate example vehicles files.

### enable\_RemoveVehiclesOnDismount

If set to true, when a user dismounts a vehicle, it will be picked up.

### enable\_RemoveVehiclesOnPlayerQuit

If set to true, when a user quits, his vehicle will be picked up.

### enable\_DestroyVehiclesOnPlayerQuit

If set to true, when a user quits, his vehicle will be destroyed.

### enable\_StopCreativeDuplication

If set to true, users will not be able to duplicate vehicles from the creative inventory.

### enable\_VehiclePlayerCollision

If set to true, vehicles will have collisions when they collide with others or with players.

{% hint style="warning" %}
In rare cases, it may cause some small lag on the first collision. If this happens, I suggest disabling this option.
{% endhint %}

### enable\_SwapEndermiteWithCheckenForLowRider

If set to true, the plugin will use chickens for the passenger seats.

### enable\_FuelCarsWhenSpawnedFromGarage

If set to true, when picking a vehicle from the garage, it will be fueled.

### enable\_UseHeadsForGUI

If set to true, the plugin will use heads to make the vehicle gui cooler.

### enable\_AntiCheatHook

If set to true, the plugin will hook with the internal Minecraft anticheat to prevent users from getting kicked for flying.

### freezeOnDestroy

If set to true, when a vehicle is destroyed, it will be frozen and not removed.

### bypassCoalInCreative

If set to true, users will be able to bypass fuel requirement when in creative mode.

### sendActionBarOnMove

If set to true, users will see a customizable message in the actionbar when moving with a vehicle.

### enableShopCooldown

If set to true, there will be a cooldown of some milliseconds when shopping items in the /qav shop to prevent bugs.

### makeVehiclesPublic

If set to true, all vehicles will be public.

### enable\_RequirePermToBuyVehicle

If set to true, players will need to have a permission to buy a vehicle.\
The permission format is: `qualityarmoryvehicles.candrive.<type>`

### enable\_VehiclesHaveTrunks

If set to true, vehicles will have a trunk to store items.

### blockAccelerationReduction

This contains a list of blocks to accelerate the vehicle.\
This is the format:

```yaml
blockAccelerationReduction:
  BLOCK_NAME: 1.0
```

You can get a list of block names [here](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/Material.html).

### enable\_RemoveVehiclesOnEmpty

If set to true, when a vehicle is empty, it will be picked up.

### BlacklistedWorlds

A list of worlds where the vehicles can't be used.

### maxYHeight

The max height for using vehicles.

### enable\_useChatForOutOfdFuelMessage

If set to true, when a vehicle will be out of fuel, a message will be sent to the user in the chat. If set to false, that message will be sent in the actionbar.

### enable\_DestroyVehiclesOnWater

If set to true, when a vehicle will touch water, it will be destroyed.

### modernPlaneMovements

If set true, the planes and helicopters will have easier controls.
