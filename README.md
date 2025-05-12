# 🚀 TelegramStickerPorter

> 一个优雅且高效的 Telegram 贴纸 / 表情克隆工具
> 支持 **贴纸包搬运**、**表情包克隆**，一键转移，极简操作！
>
> 演示机器人 [@CloneEmojiBot](https://t.me/CloneEmojiBot)

------

## ✨ 项目亮点

- 💎 支持 Telegram 贴纸 和 表情 的克隆操作
- 🧠 智能识别用户输入格式
- 🔄 支持命令格式解析自动克隆
- ⚙️ 基于 .NET 9.0 构建，性能可靠
- 🔐 使用 Telegram Bot API，简单配置即可部署

- 🧩 本软件免费无毒，可在虚拟机中运行进行长期挂机。
- ❤️ 有问题请联系 Telegram：https://t.me/v8btc

------



## 🛠 环境要求

- 最新发布版下载：https://github.com/sg688/TelegramStickerPorter/releases/latest
- 发布包提供常见的系统版本已经包含运行时。
- 如需其他可自行编译
- 请注意 使用时需具备**全局代理**或能**直连 Telegram**。
- 如果使用的`v2rayN`或者`Clash`等代理软件，**请开启Tun**
- 推荐直接部署到服务器
- 必须拥有一个已申请的 Telegram Bot Token
- 📦 图形化部署教程（适用于小白用户）：[点击查看 1Panel 部署教程](1panel.md)



## ⚙️ 配置方式

请在 `appsettings.json` 中填写您的 Bot 配置信息：

```json
{
  "Telegram": {
    "BotToken": "YOUR_BOT_TOKEN"
  }
}
```

> 🎯 你可以通过 [@BotFather](https://t.me/BotFather) 创建属于你的机器人，并获取 `BotToken`



## 📦 功能关键词

| 功能              | 关键词                |
| :---------------- | :-------------------- |
| Telegram 贴纸克隆 | TelegramStickerPorter |
| Telegram 表情搬运 | 电报贴纸搬运          |
| 电报表情克隆      | telegram表情克隆      |
| 电报贴纸搬运      | telegram贴纸搬运      |

------

## 📋 使用说明

用户与机器人对话时，只需发送以下格式命令：

```
💎 贴纸/表情克隆使用说明 💎
 
请输入您想要的目标贴纸包（或表情包）的名称，以及需要克隆的原始贴纸包（或表情包）链接，格式如下： 
 
克隆#您的贴纸包（或表情包）名称#需要克隆的贴纸包（或表情包）链接
 
例如：  
克隆#我的可爱表情包#https://t.me/addemoji/Riniba_StaticEmojiAuto  
克隆#我的酷酷的贴纸包#https://t.me/addstickers/Riniba_Packs  

🔹 克隆：命令前缀，触发克隆操作  
🔹 您的贴纸包（或表情包）名称：您希望克隆后新包的名称  
🔹 原始链接：要复制的 Telegram 表情/贴纸包链接  

请确保信息填写正确，以便程序顺利克隆哦～ 🚀
```

------

## 📃 License

[MIT License](https://github.com/Riniba/TelegramStickerPorter/blob/main/LICENSE)

------

## ❤️ 其他

> 🗨️ 有问题或者建议欢迎提 Issue，也可以直接发 PR！
> 本项目目标是打造最简洁的 Telegram 贴纸搬运工具 🛠️
