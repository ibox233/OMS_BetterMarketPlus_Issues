# BetterMarketPlus

[English](#english) | [中文](#中文)

---

## 中文

BetterMarketPlus 修复了原版 BetterMarket 模组因游戏版本更新导致的问题以及错误并增加了多个新功能和新的调整，改善了原版游戏体验。

> ⚠️ **注意**: 这个仓库仅用于 Bug 反馈和问题跟踪，不包含模组源代码。

### 🚀 功能特性

- **优化提示信息**: 改进动物、工作坊机器、树木和作物的提示信息显示
- **🆕 树木移动**: 树木现在可以在按下 `冲刺键 + 锄头` 的情况下无损移动（保留树木成长天数、收获量、收获次数、蜂巢状态）
- **🆕 洒水器范围**: 小型洒水器和大型洒水器现在会显示可浇灌的范围
- **🆕 蜂箱信息**: 蜂箱现在会显示剩余天数、周围树木和预计产出数量以及范围
- **增强金币信息**: 鼠标悬停在"金币"上时，左上角菜单中会显示更多信息
  - **🆕 财务详情**: 在原模组显示的内容上增加了销售总额、应缴税费、当前税率、净利润、总支出
- **🆕 日志界面**: 在日志界面增加了和鼠标悬停在"金币"上时相同的内容
- **自由放置**: 地面标示、墙面标示、大围栏、小围栏、纸灯笼、吊灯和壁灯可放置在任何地方
- **配方信息**: 配方现在会显示所需天数
- **45度旋转**: 物品和方块现在可以 45 度旋转
- **库存查看**: 在码头购买产品时可查看库存数量
- **🆕 多语言支持**: 默认支持简体中文、繁体中文、英语，根据游戏语言自动切换模组语言

### 🌍 语言支持

模组会根据游戏语言自动切换。翻译文件位于 `BepInEx\config\BetterMarketPlus\Localization` 目录下，格式为 `语言代码.json`。

**当前支持的语言代码**: `fr`, `de`, `ja`, `ko`, `pt`, `ru`, `es`, `tr`, `uk`

欢迎贡献翻译文件或将翻译发送给我以加入默认语言包。

### ⚙️ 兼容性

- **游戏版本**: 1.6.5+
- **模组冲突**: 与原始模组 BetterMarket 冲突，不能同时使用
- **智能兼容**: 自动检测 BetterOrder 模组的库存显示状态，并智能启用/禁用自身的库存显示功能

### 🐛 问题反馈

如果您遇到任何问题或有功能建议，请：

1. 查看 [Issues](../../issues) 页面确认问题是否已被报告
2. 如果是新问题，请 [创建新的 Issue](../../issues/new)
3. 请提供详细的问题描述、游戏版本、模组版本等信息

---

## English

BetterMarketPlus fixes issues and errors in the original BetterMarket mod caused by game version updates and adds multiple new features and adjustments, improving the original game experience.

> ⚠️ **Note**: This repository is only for bug reports and issue tracking, and does not contain the mod source code.

### 🚀 Features

- **Optimized Tooltips**: Improved tooltips for animals, workshop machines, trees, and crops
- **🆕 Tree Movement**: Trees can now be moved losslessly by holding `Sprint Key + Hoe` (preserves tree growth days, harvest amount, harvest times, beehive state)
- **🆕 Sprinkler Range**: Small and large sprinklers now display their irrigation range
- **🆕 Beehive Information**: Beehives now show remaining days, surrounding trees, estimated output quantity, and range
- **Enhanced Coin Information**: More information is displayed in the top-left menu when hovering over "coins"
  - **🆕 Financial Details**: Added total sales, taxes payable, current tax rate, net profit, and total expenses to the original mod's display
- **🆕 Journal Interface**: Added the same financial information to the journal interface
- **Free Placement**: Floor signs, wall signs, big fences, small fences, paper lanterns, chandeliers, and wall candles can be placed anywhere
- **Recipe Information**: Recipes now show required days
- **45-Degree Rotation**: Items and blocks can now be rotated by 45 degrees
- **Stock Viewing**: Stock quantity can be checked when purchasing products at the dock
- **🆕 Multi-language Support**: Default support for Simplified Chinese, Traditional Chinese, and English, with automatic language switching based on game language

### 🌍 Language Support

The mod automatically switches language based on the game language. Translation files are located in the `BepInEx\config\BetterMarketPlus\Localization` directory, in the format `LanguageCode.json`.

**Currently supported language codes**: `fr`, `de`, `ja`, `ko`, `pt`, `ru`, `es`, `tr`, `uk`

Contributions for translation files are welcome, or you can send translations to me to be included as default languages.

### ⚙️ Compatibility

- **Game Version**: 1.6.5+
- **Mod Conflicts**: Conflicts with the original BetterMarket mod, cannot be used simultaneously
- **Smart Compatibility**: Intelligently detects the inventory display status of the BetterOrder mod and automatically enables/disables its own inventory display function

### 🐛 Bug Reports

If you encounter any issues or have feature suggestions, please:

1. Check the [Issues](../../issues) page to see if the problem has already been reported
2. If it's a new issue, please [create a new Issue](../../issues/new)
3. Please provide detailed problem description, game version, mod version, and other relevant information

---

### 📝 License

This project is for issue tracking purposes only. Please refer to the actual mod distribution for licensing information.
