## How Use?

### suggestion use: [Fabric](https://fabricmc.net/use/server/)/[Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)/[Quilt](https://quiltmc.org/en/install/server/) or [Vanilla](https://www.minecraft.net/en-us/download/server) Server:

1. u need [perform basic operations](https://minecraft.fandom.com/wiki/Tutorials/Setting_up_a_server) to start server(eg: set Eula to True, etc.)
2. Un7zip and copy or cut all files in folder (must)
3. Delete all files in world folder in server directory
4. Paste copied content into the world folder
5. Download [Carpet mod](https://modrinth.com/mod/carpet) and put it in mods folder of server folder (optional)
6. Run run.cmd to start server

**Its directory looks like this(not exactly same):**

- C:\Users\Administrator\Desktop\b\world\datapacks\Servers
- ..\b\paper-1.19.4-528.jar
- ..\b\mods\fabric-carpet-1.19.4-1.4.101+v230319.jar
- ..\b\world\level.dat
- ..\b\world\dimensions\m\bw
- ..\b\world\region

**Make sure: `function-permission-level=4` in [_server.properties_](https://minecraft.fandom.com/wiki/Server.properties)**

**If you see this error, pls ignore it↓**
- **This because no Carpet mod, so some functions report an error, just ignore it:**
<img width="865" alt="WindowsTerminal_094k3vQeDo" src="https://github.com/LingLing1301/Minecraft-Server-Next-Generation/assets/65935235/c888409b-96ac-445a-9920-e11f923acbe1">

### If using another server:

**[Paper](https://papermc.io/downloads/paper)/[Folia](https://papermc.io/software/folia)/[Spigot](https://getbukkit.org/download/spigot)/[CraftBukkit](https://getbukkit.org/download/craftbukkit)/[Velocity](https://papermc.io/downloads/velocity)/[Waterfall](https://papermc.io/downloads/waterfall):**

**_NOTE: For these servers, [Minecraft-Server-Next-Generation](README.md) does not support well, u can try following steps to use_**

1. Perform [1-4 steps of the above operation](#how-use)
5. Back up and delete the DIM1, DIM-1 and dimensions folders
6. Run the server
7. Shutdown server and copy `..§aMinecraft Server Next Generation\dimensions\m\bw` folder to replace `..\b\world_m_bw\dimensions\m\bw` folder
8. The same, u need to repeat this operation to copy and replace dimensions folder in `..\dimensions\m` in all saves folders, and replace similar to server folder`..\world_m_main\dimensions\m\main`folder
9. Run server



















