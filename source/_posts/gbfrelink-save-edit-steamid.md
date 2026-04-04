---
title: GBF Relink 存档迁移笔记
date: 2024-02-03 01:03:13
category: 游戏
tags: 
    - JRPG
    - 游戏
---

## 准备

- 十六进制编辑器
- 存档文件：%LOCALAPPDATA%\GBFR\Saved\SaveGames\\**SaveData1.dat**

## 修改

1. 这里以010 Editor作为示例，打开SaveData1.dat文件，在“搜索”中选择“转到”（快捷键Ctrl + G），定位到4h位置
2. 复制好需要迁移的SteamID，在检查器中找到Int64类型（带符号或无符号皆可），应可以看到形如SteamID的数字，直接修改即可。

