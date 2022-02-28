# MinestomBrick

The goal of MinestomBrick is to allow a basis for  [Minestom](https://github.com/Minestom/Minestom) servers with plug and play extensions.

## Server

[Brick](https://github.com/MinestomBrick/Brick) is our custom server implementation for Minestom. 
It adds a colorful terminal, rolling file logging, useful startup parameters and 
a graceful stop command.

## Extensions

All extensions should work on any server implementation, they do **not** depend on [Brick](https://github.com/MinestomBrick/Brick) specifically.

| Extension                                                                         | Description                                                                  | API                |
|-----------------------------------------------------------------------------------|------------------------------------------------------------------------------|--------------------|
| [BrickI18n](https://github.com/MinestomBrick/BrickI18n)                           | Library for internationalization with reusable namespaces across extensions. | :heavy_check_mark: |
| [BrickCommandTools](https://github.com/MinestomBrick/BrickCommandTools)           | Easy to use condition builder and command group builder.                     | :heavy_check_mark: |
| [BrickPlaceholders](https://github.com/MinestomBrick/BrickPlaceholders)           | Register and use placeholders by other extensions.                           | :heavy_check_mark: |
| [BrickSidebar](https://github.com/MinestomBrick/BrickSidebar)                     | Manage multiple sidebars per player.                                         | :heavy_check_mark: |
| [BrickNametags](https://github.com/MinestomBrick/BrickNametags)                   | Manage nametags for each player.                                             | :heavy_check_mark: |
| [BrickChat](https://github.com/MinestomBrick/BrickChat)                           | Manage custom chat channels.                                                 | :heavy_check_mark: |
| [BrickWorlds](https://github.com/MinestomBrick/BrickWorlds)                       | Manage multiple worlds with custom generators.                               | :heavy_check_mark: |
| [BrickPermissions](https://github.com/MinestomBrick/BrickPermissions)             | Manage players and group permissions with persistent storage                 | :heavy_check_mark: |
| [BrickMovableStructures](https://github.com/MinestomBrick/BrickMovableStructures) | Create smooth movable structures with schematics (based on falling blocks)   | :heavy_check_mark: |
| [BrickBlockHandlers](https://github.com/MinestomBrick/BrickBlockHandlers)         | This extension adds vanilla block behavior back with custom events           | :heavy_check_mark: |
| [BrickNPCs](https://github.com/MinestomBrick/BrickNPCs)                           | Easy to use library for persistent npcs and custom traits                    | :heavy_check_mark: |
| [BrickEssentials](https://github.com/MinestomBrick/BrickEssentials)               | Adds simple vanilla commands like /teleport, /gamemode ...                   | :x:                |


## Utils

These are useful utils which can speed up the development of new extensions and add new features.

| Name                                                                          | Description                                                                                                                                     |
|-------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| [BrickScheduler](https://github.com/MinestomBrick/BrickScheduler)             | Library for async scheduling and completable futures                                                                                            |
| [BrickSchematics](https://github.com/MinestomBrick/BrickSchematics)           | Library for loading schematics                                                                                                                  |
| [BrickEntityNavigator](https://github.com/MinestomBrick/BrickEntityNavigator) | A custom entity navigator and pathfinding implementation.                                                                                       |
| [SmartInvs](https://github.com/MinestomBrick/SmartInvs)                       | A fork of the [original](https://github.com/MinusKube/SmartInvs) spigot plugin, updated for Minestom. Create inventory GUI's with a simple API. |                                                                               |

## Maven repository

```
repositories {
    maven { url "https://repo.jorisg.com/snapshots" }
}
```

## Contributions

We welcome all contributions. Most projects are also MIT Licensed so use them freely.

