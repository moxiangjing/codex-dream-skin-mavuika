# Mavuika · Art Nouveau — Codex Dream Skin Theme

一款《原神》玛薇卡（Mavuika）主题的 Codex 桌面端皮肤，基于 [Codex Dream Skin](https://github.com/Fei-Away/Codex-Dream-Skin) 的本地 CDP 注入，不修改官方程序文件。

A Genshin Impact "Mavuika" light skin for the Codex desktop app, powered by [Codex Dream Skin](https://github.com/Fei-Away/Codex-Dream-Skin). Runtime CDP injection only — the official app binaries are never touched.

![preview](theme/background.jpg)

## 特点 / Features

- 浅色新艺术风格：米白底、朱红与鎏金点缀、墨绿辅助 / Light art-nouveau palette: cream base, crimson & gold accents, deep green secondary
- 人物居右、左侧大留白，内容区干净 / Character on the right with a clean left safe area
- 含通过 Dream Skin 安全校验的 `theme.css`（磨砂质感）/ Ships a validator-safe `theme.css` (soft translucency)
- 2560×1440 背景图 / 2560×1440 background

## 安装 / Install

1. 安装 [Codex Dream Skin](https://github.com/Fei-Away/Codex-Dream-Skin) 客户端并确保托盘程序在运行 / Install the Dream Skin client and make sure the tray app is running
2. 下载 [mavuika-art-nouveau-theme.zip](https://github.com/moxiangjing/codex-dream-skin-mavuika/releases/latest/download/mavuika-art-nouveau-theme.zip)
3. 通过托盘图标「导入主题 / Import Theme」选择该 zip / Import the zip via the tray menu
4. 打开 Codex 桌面端即可看到效果 / Open the Codex desktop app

手动安装 / Manual: 把 `theme/` 目录复制到 `%LOCALAPPDATA%\CodexDreamSkin\themes\mavuika-art-nouveau\`，然后在托盘「已保存主题」中切换。你也可以直接用 [在线 Studio](https://dreamskin.cc/) 投稿到官方主题库。

## 文件结构 / Files

```
theme/
├── background.jpg   # 2560x1440 背景 / background
├── theme.json       # 主题元数据与配色 / metadata & colors
└── theme.css        # Safe CSS（已过官方校验）/ validator-safe CSS
```

## 版权 / Credits

- 主题配置 / Theme config: MIT
- 玛薇卡角色 © HoYoverse（米哈游）。本皮肤为同人非商业作品，与米哈游及 OpenAI 均无关联 / Mavuika © HoYoverse. Unofficial fan work, not affiliated with HoYoverse or OpenAI.
- 背景图 / Background art: 由本仓库作者制作 / created by the repo author.
