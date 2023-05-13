## English

### It is recommended to use [Fabric](https://fabricmc.net/use/server/)/[Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)/[Quilt](https://quiltmc.org/en/install/server/) or [Vanilla](https://www.minecraft.net/en-us/download/server) Server:

1. You need to [perform basic operations](https://minecraft.fandom.com/wiki/Tutorials/Setting_up_a_server) to start the server(eg: set Eula to True, etc.)
2. Un7zip and copy or cut all files in the folder (It is necessary)
3. Delete all files in the world folder in the server directory
4. Paste the copied content into the world folder
5. Download the [Carpet mod](https://modrinth.com/mod/carpet) and put it in the mods folder of the server folder
6. Run run.cmd to start the server (maybe call it something else, it's up to you)

**Its directory looks like this(not exactly the same):**

- C:\Users\Administrator\Desktop\b\world\datapacks\Servers
- ..\b\paper-1.19.4-528.jar
- ..\b\mods\fabric-carpet-1.19.4-1.4.101+v230319.jar
- ..\b\world\level.dat
- ..\b\world\dimensions\m\bw
- ..\b\world\region

**Make sure: `function-permission-level=4` in [_server.properties_](https://minecraft.fandom.com/wiki/Server.properties)**

**If you see this error, please ignore it↓**
- **This is because there is no Carpet mod, so some functions report an error, just ignore it:**
<img width="865" alt="WindowsTerminal_094k3vQeDo" src="https://github.com/LingLing1301/Minecraft-Server-Next-Generation/assets/65935235/c888409b-96ac-445a-9920-e11f923acbe1">

### If using another server:

**[Paper](https://papermc.io/downloads/paper)/[Folia](https://papermc.io/software/folia)/[Spigot](https://getbukkit.org/download/spigot)/[CraftBukkit](https://getbukkit.org/download/craftbukkit)/[Velocity](https://papermc.io/downloads/velocity)/[Waterfall](https://papermc.io/downloads/waterfall):**

**_NOTE: For these servers, Minecraft-Server-Next-Generation does not support well, you can try the following to use_**

1. You need to [perform basic operations](https://minecraft.fandom.com/wiki/Tutorials/Setting_up_a_server) to start the server(eg: set Eula to True, etc.)
2. Un7zip and copy or cut all files in the folder (It is necessary)
3. Delete all files in the world folder in the server directory
4. Paste the copied content into the world folder
5. Back up and delete the DIM1, DIM-1 and dimensions folders
6. Run the server
7. Shut down the server and copy the `..§aMinecraft Server Next Generation\dimensions\m\bw` folder to replace the `..\b\world_m_bw\dimensions\m\bw` folder
8. By analogy, you need to repeat this operation to copy and replace the dimensions folder in `..\dimensions\m` in all archive folders, and replace similar to the server folder`..\world_m_main\dimensions\m\main`folder
9. Run the server



















