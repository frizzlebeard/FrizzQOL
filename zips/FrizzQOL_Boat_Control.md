# FrizzQOL Boat Control

Sets the chest size and cargo weight cap for each boat, and lets the hammer take a ship apart.

## Chest size

`BepInEx/config/com.frizzqol.boatcontrol.cfg`

The first launch writes one section per boat, using that boat's normal chest size.

| Setting | What it does |
| --- | --- |
| Width | Chest columns. 1 to 8. 0 or less keeps the normal width. |
| Height | Chest rows. 0 or less keeps the normal height. |
| MaxWeight | Most cargo weight the chest will hold. 0 or less means no cap. |

Empty a chest before you shrink it, or the items that no longer fit are lost.

## Taking a ship apart

`HammerDeconstruct` under `[General]` defaults to on. Hammer middle-click drops the cargo on the ground, then returns the boat materials. Someone standing on the ship blocks it.

## Multiplayer

Install this on the dedicated server and on every client. Use the same config on each of them.

## Source

https://github.com/frizzlebeard/FrizzQOL.BoatControl

## Install

Install with r2modman or the Thunderstore Mod Manager.

To install by hand, copy `FrizzQOL.BoatControl.dll` into `BepInEx/plugins`.

## Requirements

- Valheim
- [BepInExPack for Valheim](https://thunderstore.io/c/valheim/p/denikson/BepInExPack_Valheim/)

## License

[MIT License](https://opensource.org/licenses/MIT). You can use, copy, change, and share this mod. The LICENSE file shipped with the package has the full text.
