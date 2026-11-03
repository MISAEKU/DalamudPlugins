# DalamudPlugins

MISAEKU 维护的 Dalamud 第三方插件库（Dalamud Plugin Repo）。

## 使用方式

1. 打开游戏内 `/xlsettings`（或启动器设置）→ Dalamud → **第三方插件库 / 实验性插件库**，填入本仓库链接：

   ```
   https://raw.githubusercontent.com/MISAEKU/DalamudPlugins/main/pluginmaster.json
   ```

2. 点击设置页上方的**保存**按钮，重启游戏（或重新加载 Dalamud）。
3. 打开 `/xlplugins` → 插件安装 → 搜索 **Smart Npc** → 安装。
4. 游戏内输入 `/smartnpc` 打开控制面板。

> 更新插件同样走这里：插件列表里直接点更新即可。

## 仓库插件列表

| 名称 | 游戏版本 | 描述 |
| --- | --- | --- |
| [Smart Npc](https://github.com/MISAEKU/SmartNPC) | 7.5 | 凭空造一个会跟着你的智能 NPC：可换装、可做表情动作、会自己说话 |

## 插件维护者：发布新版本

1. 在 SmartNPC 仓库发布新 Release（tag = 版本号，资产 `latest.zip`）
2. 更新本仓库 `pluginmaster.json` 的 `AssemblyVersion` 与两个 `DownloadLink` 中的版本号
3. 提交推送后，玩家端重新加载插件库即可拉到新版本

## 免责声明

- 本插件库仅聚合第三方插件链接，插件功能与维护归各自作者所有。
- 使用任何第三方工具都可能伴随潜在风险，请自行评估并承担后果。
