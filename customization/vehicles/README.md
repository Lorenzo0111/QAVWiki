---
description: Learn how to create a vehicle
---

# Creating a vehicle

For creating a vehicle I suggest editing a premade configuration.

These are all settings.

### vehicle\_type

The vehicle type.\
Available types: Car, Plane, Boat, Helicopter, Train, Drill, Tractor.

### name

The vehicle name, it must be unique.

### id

The vehicle id, it must be unique.

### displayname

The vehicle display name.

### center

A vector displaying the center of that vehicle.

### passagers

A list of vectors representing the position of the passengers' seats.

### stopMeleeDamage

If set to true, the vehicle will not be damaged by guns.

### RequiresFuel

If set to true, the vehicle will require the fuel for being used.

### widthOffset

The width of the hitbox

### heightOffset

The height of the hitbox

### vehicle\_texture\_material

The item of the vehicle

### maxHealth

The max health of the vehicle

### cost

The cost of the vehicle in the shop. To disable it, set it to -1.

### InputManager

A map of registered inputs.

Input types: HONK, SIREN, MININUKE\_BOMBER, TNT\_BOMBER, 40MM\_LAUNCHER, BULLETS\_556.

### ItemLore

A list of strings for the item lore

### TurnSpeedInRadians

The turn speed

### trunksize

The size of how many items can the trunk contain.

### allowedInShop

If set to true, players will be able to buy the vehicle from the shop.

### maxAcceleration

The max speed for the vehicle

### baseAcceleration

The base speed for the vehicle

### maxReverseAcceleration

The max reverse speed for the vehicle

### canJumpOnBlocks

If set to true, the vehicle will be able to jump on blocks

### jumpHeight

The height of how many blocks can the vehicle jump

### model.ModelSize

Current available options: BABY\_ARMORSTAND\_HEAD, ADULT\_ARMORSTAND\_HEAD, ADULT\_ARMORSTAND\_HAND, TURTLE

### rotationMultiplier

A number that is multiplied by the calculated rotation.

### sound

The id of the sound that is played while driving

### soundVolume

The volume of the sound

### driverseat.Offset

The vector that rapresents the position of the driver seat.
