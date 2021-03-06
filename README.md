# MCGalaxy-Plugins
Some custom command and plugins for MCGalaxy.

### Usage

#### Commands 
- Place the .cs file in */extra/commands/source*
- /compile [command name]
- /cmdload [commd name]
- Add the command name (e.g. GBInsert) to text/cmdautoload.txt to make it load on server start.
#### Plugins
- Place the .cs file in */plugins*
- /pcompile [plugin name]
- /pload [plugin name]
- Plugins automatically load on server start.

### List
| Name | Description |
| ------------- | -----|
| **BinVoxImport** | Imports [binvox](http://www.patrickmin.com/binvox/) files from /extra/import. BinBox is useful for voxelising .obj models.
| **CmdBiggestTables** | Lists the database tables with most rows. Unlikely to be useful except for debugging.
| **CmdGBInsert** | Reorders a global block's position in the inventory.
| **CmdImpersonate** | Fake a chat message as if it came from another player.
| **CmdMapHack** | Allows you to bypass -hax on your own /os maps. (or ranks >= the extra permission)
| **CmdSetSoftwareName** | Sets the name of the software shown in /sinfo and in the server list.
| **GoodlyEffects** | Adds support for CustomParticles CPE. Documentation can be found [here](documentation/GoodlyEffects.md).
| **KickJini** | Prevents people using Jini client from logging in.
| **LockedModel** | Forces players to only use specified model(s) on a map.
| **MagicaVoxelImport** | Importa [MagicaVoxel](https://ephtracy.github.io/) files from /extra/import.
| **Marry** | Allows you to show as married to another player in /whois.
| **PluginNoTp** | Prevents using /tp on certain maps. (you may need to change the source code)
| **Rainbow** | Makes the %r custom colour constantly change in rainbow pattern/ (you must define %r first)
| **TeamChatPlugin** | Allows using *=message* as shortcut for */team message*.