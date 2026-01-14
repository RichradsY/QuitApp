# QuitApp
戒了没APP （后续推出国际版本）
# 戒了没 - 万能戒断计数器

> **"你已经X天没碰XX了"**

一款极简的戒断计数器 iOS App，帮助用户记录戒烟、戒酒、戒糖、戒前任等各种戒断行为的坚持天数。

![Platform](https://img.shields.io/badge/Platform-iOS%2016+-blue.svg)
![Swift](https://img.shields.io/badge/Swift-5.9-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## ✨ 功能特点

- 🔢 **极简计数** - 大字显示已坚持天数，一目了然
- 📁 **多项目管理** - 同时追踪多个戒断目标
- 💪 **心理激励** - 点击"我在坚持"获得浮动鼓励语
- 📊 **历史记录** - 查看每次尝试的开始/结束时间及破戒原因
- 🎨 **分享卡片** - 4种渐变样式，一键保存到相册
- 🎉 **完成庆祝** - 成功戒断后的彩纸庆祝动画
- 🌙 **深色模式** - 自动适配系统主题

## 📱 预设类别

| 健康类 | 情感类 | 习惯类 |
|--------|--------|--------|
| 🚬 戒烟 | 💔 戒前任 | 📱 戒手机 |
| 🍺 戒酒 | 😢 戒哭泣 | 🎮 戒游戏 |
| 🍰 戒糖 | 😠 戒发脾气 | 🛒 戒剁手 |
| 🥤 戒奶茶 | 🗣️ 戒抱怨 | 📺 戒刷剧 |
| ☕ 戒咖啡 | | 📹 戒短视频 |

支持 **自定义戒断项目** 和 **自定义图标**。

## 🛠 技术栈

- **语言**: Swift 5.9+
- **UI框架**: SwiftUI
- **数据存储**: UserDefaults + JSON
- **最低版本**: iOS 16.0

## 📦 项目结构

```
QuitApp/
├── QuitApp.swift              # App 入口
├── ContentView.swift          # 主视图
├── Models/
│   ├── QuitItem.swift         # 戒断项模型
│   ├── Relapse.swift          # 破戒记录模型
│   └── PresetCategory.swift   # 预设类别
├── Views/
│   ├── HomeView.swift         # 主页 + 组件
│   ├── CreateView.swift       # 新建戒断
│   ├── RelapseView.swift      # 破戒确认
│   └── ShareCardView.swift    # 分享卡片
├── Services/
│   └── StorageService.swift   # 数据持久化
└── Extensions/
    ├── Color+Extensions.swift
    └── Date+Extensions.swift
```

如果您有任何问题或者需求 请通过以下方式联系我们：

- 📧 邮箱：[yangshengxing88@163.com]
- 🐙 GitHub：[https://github.com/RichradsY/QuitApp]
