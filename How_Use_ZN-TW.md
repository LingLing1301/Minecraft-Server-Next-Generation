## 如何使用?

### 推薦使用[Fabric](https://fabricmc.net/use/server/)/[Forge](https://files.minecraftforge.net/net/minecraftforge/forge/)/[Quilt](https://quiltmc.org/en/install/server/)或者[Vanilla](https://www.minecraft.net/en-us/download/server)服務端:

1. 你需要[進行開服的基本操作](https://minecraft.fandom.com/wiki/Tutorials/Setting_up_a_server)就像大部分伺服器開服一樣(比如設置Eula=true...)
2. 解壓,然後復製或剪下裡面的所有檔案 (必須如此操作)
3. 刪除伺服器所在資料夾內的world資料夾內的全部檔案
4. 把複製的檔案貼到world資料夾中
5. 下載[Carpet mod](https://modrinth.com/mod/carpet)模組,然後放到伺服器資料夾中的mods資料夾裡 (不必須)
6. 執行run.cmd來啟動伺服器(也許叫其他名字,這取決於你)

**它的目錄應該是如此(不完全相同):**

- C:\Users\Administrator\Desktop\b\world\datapacks\Servers
- ..\b\paper-1.19.4-528.jar
- ..\b\mods\fabric-carpet-1.19.4-1.4.101+v230319.jar
- ..\b\world\level.dat
- ..\b\world\dimensions\m\bw
- ..\b\world\region

**確保: [_server.properties_](https://minecraft.fandom.com/wiki/Server.properties)中的`function-permission-level=4`**

**如果看到此報錯,請忽視它↓**
- **這是因為沒有Carpet模組導致的,這會導致部分函數無法使用,可以忽略它:**
<img width="865" alt="WindowsTerminal_094k3vQeDo" src="https://github.com/LingLing1301/Minecraft-Server-Next-Generation/assets/65935235/c888409b-96ac-445a-9920-e11f923acbe1">

### 如果使用其他伺服器:

**[Paper](https://papermc.io/downloads/paper)/[Folia](https://papermc.io/software/folia)/[Spigot](https://getbukkit.org/download/spigot)/[CraftBukkit](https://getbukkit.org/download/craftbukkit)/[Velocity](https://papermc.io/downloads/velocity)/[Waterfall](https://papermc.io/downloads/waterfall):**

**_注意: 對於這些伺服器, [Minecraft-Server-Next-Generation](README_ZH-TW.md)的支援不是很好,但你可以嘗試使用它_**

1. 進行[上述操作的1-4步驟](#%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8)
2. 備份並刪除world文件夾內的DIM1,DIM-1和dimensions資料夾
3. 啟動伺服器
4. 關閉伺服器,複製`..§aMinecraft Server Next Generation\dimensions\m\bw`中的檔案,替換`..\b\world_m_bw\dimensions\m\bw`中的檔案
5. 以此類推,需要重複此操作複製替換所有儲存檔案資料夾中`..\dimensions\m`中的所有資料夾,複製替換到服務端目錄中類似`..\world_m_main\dimensions\m\main`的資料夾
6. 啟動伺服器



















