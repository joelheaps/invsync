## Fork

This project was forked from [the upstream Invsync project](https://github.com/MrNavaStar/invSync) and updated to a new version of Minecraft expediently and lazily with LLM assistance.  There may be dragons 🐉, there may not.  I'm running this on a casual server I host, and if I get time for a more thorough review and cleanup of the port, perhaps I'll remove this scary disclaimer.

Last tested and used on a pair of Minecraft Fabric 26.2 servers.

A [Mise](https://mise.jdx.dev/) configuration and build task has been added for convenience.  To build the JAR to install on a server, run:
```sh
mise run build
# builds to build/libs/
```

---

<img src="https://raw.githubusercontent.com/MrNavaStar/invSync/master/src/main/resources/assets/invsync/icon.png" width="300" height="300">

# InvSync

This is a fabric mod that Allows you to sync player inventories, health, food level, experience, score, status effects and advancements across multiple servers or single player minecraft worlds! This is accomplished using an sql database (SQLite and MySQL supported. SQLite will be setup automatically, you must set up MySQL). Most mods should have no problem running along side, and modded items will also be sync'd.

This mod uses [SQLib](https://github.com/MrNavaStar/SQLib) as a backend. Feel free to use it in your own projects!

## Requirements

- This mod requires [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) 
- You can get the mod on [Modrith](https://modrinth.com/mod/invsync)

## Getting Started

Setup is very simple. Drop the mod into your mods folder on all the servers you want to sync. Starting a server will generate a config. The mod will not run until you edit the config.

## IMPORTANT NOTES 

- Configs MUST be identical between all participating servers in order for the mod to function correctly.
- This mod is known to have issues with: **GolfV**

## Issues And Requests

If you find any bugs or glitches, be sure to make a bug report under issues and I will do my best to fix it! Just as well if you have a cool idea for something that I should add, let me know and I will consider adding it!
