# MinestomBrick

The goal of MinestomBrick is to allow a basis for  [Minestom](https://github.com/Minestom/Minestom) servers with plug and play extensions.

## [Brick](https://github.com/MinestomBrick/Brick)

[Brick](https://github.com/MinestomBrick/Brick) is our custom server implementation for Minestom. 
It adds a colorful terminal, rolling file logging, port and online-mode startup parameters and 
a graceful stop command.

## Extensions

All extensions should work on any server implementation, they do **not** depend on [Brick](https://github.com/MinestomBrick/Brick) specifically.

| Extension                                                               | Description                                                                                                                                                         | API |
|-------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|
| [BrickPlaceholders](https://github.com/MinestomBrick/BrickPlaceholders) | A simple placeholder extension with an API to register and consume placeholders. Also works with [Adventure](https://github.com/KyoriPowered/adventure) components. | Yes |
| [BrickSidebar](https://github.com/MinestomBrick/BrickSidebar)           | A simple sidebar extension with layering so multiple sidebars can be managed.                                                                                       | Yes |
| [BrickNametags](https://github.com/MinestomBrick/BrickNametags)         | A simple nametag extension to give nametag prefixes and suffixes to players.                                                                                        | Yes |
| [BrickChat](https://github.com/MinestomBrick/BrickChat)                 | A simple chat plugin to handle multiple chat channels.                                                                                                              | Yes |
| [BrickWorlds](https://github.com/MinestomBrick/BrickWorlds)             | A simple world management extension for creating, saving and loading worlds.                                                                                        | Yes |
| [BrickEssnetials](https://github.com/MinestomBrick/BrickEssentials)     | A simple extension which adds some vanilla commands and features like /gamemode, /teleport, ...                                                                     | No  |


## Utils

These are useful utils which can speed up the development of new extensions and add new features.

| Name                                                      | Description                                                                                                                                     |
|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| [BrickUtils](https://github.com/MinestomBrick/BrickUtils) | Contains multiple small modules which can be added to your project: translations, commands, scheduling and a database orm.                      |
| [SmartInvs](https://github.com/MinestomBrick/SmartInvs)   | A fork of the [original](https://github.com/MinusKube/SmartInvs) spigot plugin, updated for Minestom. Create inventory GUI's with a simple API. |                                                                               |

## Maven repository

```
repositories {
    maven { url "https://repo.jorisg.com/snapshots" }
}
```

## Contributions

We welcome all contributions. Most projects are also MIT Licensed so use them freely.

