# 游戏存档使用说明

每个子目录的名称对应 Steam 云存档中显示的游戏名称。  
子目录中的 `README.md` 文件说明了该游戏存档的位置。  
将子目录中的存档文件夹复制并替换到对应的游戏存档位置，即可使用存档。

对于没有云存档的游戏，其存档文件位于 `_NO STEAM CLOUD` 目录中。

---

## 常见游戏存档位置（Windows）

### 1. **Steam 游戏数据**
   ```plaintext
   ...\Steam\userdata\<Steam 好友代码>\<AppID>\remote
   ```
### 2. **游戏安装位置**
   GameInstall ：
   ```plaintext
   ...\steam\steamapps\common\<游戏名>\
   ```
### 3. **文档目录** 
   ```plaintext
   %USERPROFILE%\Documents\(<开发团队/公司/发行商名>\)<游戏名>\
   ```
   WinMyDocuments ：
   ```plaintext
   %OneDrive%\文档\(<开发团队/公司/发行商名>\)<游戏名>\
   ```
   ```plaintext
   %OneDrive%\文档\My Games\<游戏名>\
   ```
### 3. **本地应用数据**  
   WinAppDataLocal ：
   ```plaintext
   %USERPROFILE%\AppData\Local\<游戏名>\
   ```  
   WinAppDataLocalLow ：
   ```plaintext
   %USERPROFILE%\AppData\LocalLow\(<开发团队/公司/发行商名>\)<游戏名>\
   ```
### 4. **Roaming 配置**  
   ```plaintext
   %USERPROFILE%\AppData\Roaming\<游戏名>\
   ```
### 6. **系统保存**
   WinSavedGames :
   ```plaintext
   %UserProfile%\Saved Games\<游戏名>\
   ```

---

## 如何查找 Steam 游戏的 AppID

- **方法 1**：在 Steam 商店页面的 URL 中查找数字部分，即为 AppID。  
- **方法 2**：访问 [SteamDB](https://steamdb.info/)，搜索游戏名称。  
- **方法 3**：在 Steam 客户端中，右键游戏 -> 属性 -> 更新，查看 AppID。

---
