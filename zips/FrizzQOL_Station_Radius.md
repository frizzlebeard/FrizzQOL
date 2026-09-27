# FrizzQOL Station Radius

Sets the build circle and the use distance for each crafting station.

## Config

`BepInEx/config/com.frizzqol.stationradius.cfg`

The first launch writes one section per station, using the vanilla distances.

| Setting | What it does |
| --- | --- |
| BuildRadius | Build circle in meters. 0 or less keeps vanilla. |
| UseRadius | Use and open distance in meters. 0 or less keeps vanilla. |

Workbench extensions still add their vanilla bonus on top of BuildRadius.

## Multiplayer

Install this on the dedicated server and on every client. Use the same config on each of them.

## Source

https://github.com/frizzlebeard/FrizzQOL.StationRadius

## Install

Install with r2modman or the Thunderstore Mod Manager.

To install by hand, copy `FrizzQOL.StationRadius.dll` into `BepInEx/plugins`.

## Requirements

- Valheim
- [BepInExPack for Valheim](https://thunderstore.io/c/valheim/p/denikson/BepInExPack_Valheim/)

## License

[MIT License](https://opensource.org/licenses/MIT). You can use, copy, change, and share this mod. The LICENSE file shipped with the package has the full text.
