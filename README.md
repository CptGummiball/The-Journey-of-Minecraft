<h1 align="center">The Journey of Minecraft</h1>

<p align="center"><i>Every world has a story. This one is yours.</i></p>

<p align="center">
  <a href="https://modrinth.com/modpack/the-journey-of-minecraft"><img alt="Modpack on Modrinth" src="https://img.shields.io/badge/Modpack-Modrinth-1bd96a?style=for-the-badge&logo=modrinth&logoColor=white"></a>
  <a href="https://github.com/CptGummiball/The-Journey-of-Minecraft/releases/latest"><img alt="Server package" src="https://img.shields.io/badge/Server%20package-Releases-f2c14e?style=for-the-badge&logo=github&logoColor=white"></a>
  <br>
  <img alt="Minecraft 1.21.1" src="https://img.shields.io/badge/Minecraft-1.21.1-5b8c3a?style=flat-square">
  <img alt="Fabric" src="https://img.shields.io/badge/Loader-Fabric%200.19.5-dbd0b4?style=flat-square">
  <img alt="Java 21" src="https://img.shields.io/badge/Java-21-e07a2f?style=flat-square">
</p>

**The Journey of Minecraft** is a Vanilla+ survival modpack for Minecraft 1.21.1 (Fabric). It is still Minecraft —
your world, your rules — with one thing the base game never had: a journal that follows you from your first log to the
dragon and beyond. Eight chapters, 38 main steps and 36 side paths, in English and German. Nothing is ever locked.

| I want to … | Go to |
|---|---|
| **play the modpack** | [Modrinth → The Journey of Minecraft](https://modrinth.com/modpack/the-journey-of-minecraft) |
| **host a server** | [Releases](https://github.com/CptGummiball/The-Journey-of-Minecraft/releases/latest) → `The-Journey-of-Minecraft-Server-<version>.zip` |
| **report a bug or suggest something** | [Issues](https://github.com/CptGummiball/The-Journey-of-Minecraft/issues) |

## Dedicated server

The server package contains **no third-party mod files** — only the pack's own content, configs and a small installer
that downloads every server-side mod from its official source (Modrinth CDN, FabricMC) and verifies it with SHA-512.

**Quick start** (Java 21 required):

1. Download `The-Journey-of-Minecraft-Server-<version>.zip` from the [latest release](https://github.com/CptGummiball/The-Journey-of-Minecraft/releases/latest)
   and unzip it into an empty folder.
2. Run `java InstallServer.java` inside that folder.
3. Read the [Minecraft EULA](https://aka.ms/MinecraftEULA) and set `eula=true` in `eula.txt` if you accept it.
4. Start with `start.bat` (Windows) or `sh start.sh` (Linux/macOS).

Players need the **same pack version** from Modrinth as the server package (both use the same version number).
Every player keeps their own journal; late joiners catch up automatically.
Updating, RAM and multiplayer details are in `README_SERVER.md` inside the package.

## License

The pack's own content is MIT-licensed (`LICENSE.txt` in the server package). Third-party mods are not included;
they are downloaded from their official Modrinth pages and keep their own licenses (`THIRD_PARTY.txt`).

*Not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.*
