# DalamudPlugins-TW

台服 FFXIV 專用的 Dalamud 插件倉庫，提供 API12 版本的插件。

## 使用方式

1. 開啟 Dalamud 設定
2. 進入「實驗性功能」
3. 在「自訂插件儲存庫」加入以下 URL：

```
https://raw.githubusercontent.com/cycleapple/DalamudPlugins-TW/main/repo.json
```

4. 儲存後即可在插件安裝器中看到這些插件

## 可用插件

| 插件 | 版本 | 說明 |
|------|------|------|
| **Penumbra** | 9.0.0.1 | Mod 載入器與管理工具 |
| **Simple Heels** | 0.10.6.2 | 穿著 Mod 高跟鞋時調整角色位置 |
| **Brio** | 0.5.1.0 | GPose 增強工具，用於拍照與動作控制 |
| **Glamourer** | 1.4.0.1 | 外觀修改與儲存工具（需要 Penumbra）- **已修改支援中文名稱** |
| **Customize+** | 2.0.7.22 | 透過編輯骨骼參數自訂角色外觀 |
| **Aetherment** | 0.3.3 | Mod 瀏覽、安裝與自動更新工具 |

## 為什麼需要這個倉庫？

台服使用的 Dalamud 版本為 API12，而官方插件倉庫已更新至 API13。這導致許多插件無法在台服上使用。

本倉庫提供這些插件的 API12 相容版本，讓台服玩家也能使用這些實用的插件。

## 相關連結

- [台服 Dalamud (yanmucorp)](https://github.com/yanmucorp/Dalamud)
- [Penumbra 官方](https://github.com/xivdev/Penumbra)
- [Simple Heels 官方](https://github.com/Caraxi/SimpleHeels)
- [Brio 官方](https://github.com/Etheirys/Brio)
- [Glamourer 官方](https://github.com/Ottermandias/Glamourer)
- [Customize+ 官方](https://github.com/Aether-Tools/CustomizePlus)
- [Aetherment 官方](https://github.com/Sevii77/aetherment)

## 修改說明

### Glamourer

此版本的 Glamourer 是基於 [Ottermandias/Glamourer v1.4.0.1](https://github.com/Ottermandias/Glamourer/releases/tag/1.4.0.1) 修改而成。

**修改內容：**
- 修復中文/台服客戶端無法偵測玩家角色的問題
- 原版僅顯示 NPC，不顯示 LocalPlayer 和其他玩家

**問題原因：**
原版的 `VerifyPlayerName()` 僅接受西方字母 (a-z)，導致中文名稱驗證失敗。

**修改的檔案：**
- `Penumbra.GameData/Interop/Actor.cs` - 關閉嚴格的名稱/世界驗證

**Fork 來源：**
- [cycleapple/Glamourer](https://github.com/cycleapple/Glamourer/tree/fix-player-detection)
- [cycleapple/Penumbra.GameData](https://github.com/cycleapple/Penumbra.GameData/tree/fix-non-western-clients)

## 注意事項

- 這些插件是從官方源碼編譯的 API12 版本
- Glamourer 經過修改以支援中文名稱
- 版本可能落後於官方最新版本
- 如有問題請在 Issues 中回報

## 授權

各插件依照其原始授權條款發布。本倉庫僅提供編譯後的二進位檔案供台服玩家使用。
