## 如何使用?

### 推荐使用[Fabric](https://fabricmc.net/use/server/)/[Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)/[Quilt](https://quiltmc.org/en/install/server/)或者[Vanilla](https://www.minecraft.net/en-us/download/server)服务端:

1. 你需要[进行开服的基本操作](https://minecraft.fandom.com/wiki/Tutorials/Setting_up_a_server)就像大部分服务器开服一样(比如设置Eula=true...)
2. 解压,然后复制或剪切里面的所有文件 (必须这么做)
3. 删除服务端所在文件夹内的world文件夹内的全部文件
4. 把复制的文件粘贴到world文件夹
5. 下载[Carpet mod](https://modrinth.com/mod/carpet)模组，然后放到服务端文件夹中的mods文件夹 (不必须)
6. 运行run.cmd来启动服务器(也许叫其他名字,这取决于你)

**它的目录应该是这样的(不完全相同):**

- C:\Users\Administrator\Desktop\b\world\datapacks\Servers
- ..\b\paper-1.19.4-528.jar
- ..\b\mods\fabric-carpet-1.19.4-1.4.101+v230319.jar
- ..\b\world\level.dat
- ..\b\world\dimensions\m\bw
- ..\b\world\region

**确保:[_server.properties_](https://minecraft.fandom.com/wiki/Server.properties)中的`function-permission-level=4`**

**如果看到此报错,请忽略它↓**
- **这是因为没有Carpet模组导致的,这会导致部分函数无法使用,可以忽略它:**
<img width="865" alt="WindowsTerminal_094k3vQeDo" src="https://github.com/LingLing1301/Minecraft-Server-Next-Generation/assets/65935235/c888409b-96ac-445a-9920-e11f923acbe1">

### 如果使用其他服务端:

**[Paper](https://papermc.io/downloads/paper)/[Folia](https://papermc.io/software/folia)/[Spigot](https://getbukkit.org/download/spigot)/[CraftBukkit](https://getbukkit.org/download/craftbukkit)/[Velocity](https://papermc.io/downloads/velocity)/[Waterfall](https://papermc.io/downloads/waterfall):**

**_注意: 对于这些服务端, [Minecraft-Server-Next-Generation](README.md)的支持不是很好,但你可以尝试使用它_**

1. 进行[上述操作的1-4步骤](##推荐使用)
2. 备份并删除world文件夹内的DIM1,DIM-1和dimensions文件夹
3. 启动服务器
4. 关闭服务器,复制`..§aMinecraft Server Next Generation\dimensions\m\bw`中的文件,替换`..\b\world_m_bw\dimensions\m\bw`中的文件
5. 以此类推,需要重复此操作复制替换所有存档文件夹中`..\dimensions\m`中的所有文件夹,复制替换到服务端目录中类似`..\world_m_main\dimensions\m\main`的文件夹
6. 启动服务器



















