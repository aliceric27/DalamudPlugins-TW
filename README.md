# DalamudPlugins-TW

台服 FFXIV 專用的 Dalamud 插件倉庫，提供 API12 版本的插件。
感謝 [Discord神秘社團](https://discord.gg/KtGprs493S) 各位大佬提供。

## 使用方式

1. 開啟 Dalamud 設定
2. 進入「實驗性功能」
3. 在「自訂插件儲存庫」加入以下 URL：

```
https://raw.githubusercontent.com/aliceric27/DalamudPlugins-TW/main/repo.json
```

4. 儲存後即可在插件安裝器中看到這些插件

## 檔案命名規則

本倉庫內的插件壓縮檔採用固定命名格式，方便管理與回溯版本：

```
plugins/<PluginFolder>/<InternalName>-<AssemblyVersion>.zip
```

`repo.json` 內指向本倉庫的下載連結也會使用相同檔名（不使用 `latest.zip`）。

## 可用插件

不保證與其他插件的相容性，請自行斟酌使用
### 🔴用安自負🔴🔴用安自負🔴🔴用安自負🔴


| 插件 | 版本 | 說明 |
|------|------|------|
| [**Daily Routines**](https://github.com/AtmoOmen/DalamudPlugins) | 1.8.3.4 | 必備魔法DR |
| [**Bossmod Reborn**](https://github.com/FFXIV-CombatReborn/BossmodReborn) | 7.2.5.109 | 顯示技能傷害範圍&其他 |
| [**Rotation Solver Reborn**](https://github.com/FFXIV-CombatReborn/RotationSolverReborn) | 7.2.5.122 | 一鍵技能循環 |
| [**Splatoon**](https://github.com/PunishXIV/Splatoon) | 3.8.1.5 | 場景繪製點線面 |
| [**Wrath Combo**](https://github.com/MeowZWR/WrathCombo) | 1.0.1.18 | 一鍵技能循環收錄的是漢化版 |
| [**AntiAfkKick**](https://github.com/NightmareXIV/AntiAfkKick) | 2.1.0.7 | 防止閒置太久被踢下線 |
| [**AutoRetainer**](https://github.com/PunishXIV/AutoRetainer) | 4.5.0.4 | 雇員相關 |
| [**Saucy**](https://github.com/PunishXIV/Saucy) | 1.4.2.0 | 金蝶相關 |
| [**NoClippy**](https://github.com/UnknownX7/NoClippy) | 0.5.0.18 | 不知道是二插還三插 |
| [**NecroLens**](https://github.com/Jukkales/NecroLens) | 1.0.8.11 | 深宮小精靈 |
| [**MidiBard 2**](https://midibard.org) | 3.1.0.0 | 演奏 |
| [**GatherBuddy Reborn**](https://github.com/AtmoOmen/GatherBuddyReborn) | 7.2.5.1 | 採集小精靈 |
| [**Artisan**](https://github.com/MeowZWR/Artisan) | 4.0.3.46 | 生產小精靈 |
| [**Burning Down the House**](https://github.com/LeonBlade/BDTHPlugin) | 1.6.9 | 裝修公司 |
| [**Raphael.Dalamud**](https://github.com/Dalamud-DailyRoutines/Raphael.Dalamud) | 0.0.3.0 | DR有一個功能需要用到 |
| [**Something Need Doing**](https://github.com/Jaksuhn/SomethingNeedDoing) | 0.0.0.0 | 巨集擴展 |
| [**TextAdvance**](https://github.com/NightmareXIV/TextAdvance) | 3.2.4.5 | 跳過劇情對話 |
| [**Lifestream**](https://github.com/NightmareXIV/Lifestream) | 2.5.1.15 | 一鍵傳送 |
| [**vnavmesh**](https://github.com/awgil/ffxiv_navmesh) | 0.4.0.2 | 自動尋路 / 移動工具 |
| [**Boss Mod**](https://github.com/awgil/ffxiv_bossmod) | 0.1.4.0 | Boss 機制輔助 |
| [**AutoDuty**](https://github.com/ffxivcode/AutoDuty) | 0.0.0.0 | 自動副本（需搭配 BossMod、vnavmesh 與循環插件） |
| [**Pixel Perfect**](https://github.com/Haplo064/PixelPerfect) | 3.3.1.0 | 顯示碰撞箱 / 站位輔助 |
| [**LazyLoot**](https://github.com/PunishXIV/LazyLoot) | 5.3.2.1 | 自動擲骰 / 撿取相關 |
| [**Questionable**](https://git.carvel.li/liza/Questionable) | 5.23 | 任務助手（需搭配 vnavmesh/TextAdvance/Lifestream） |
| **FF14 傷害統計** | 1.0.0.0 | 即時 DPS 統計 |

## 為什麼需要這個倉庫？

台服使用的 Dalamud 版本為 API12，而官方插件倉庫已更新至 API13。這導致許多插件無法在台服上使用。
本倉庫提供這些插件的 API12 相容版本，讓台服玩家也能使用這些實用的插件。

## 授權

各插件依照其原始授權條款發布。
