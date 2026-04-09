# GDS Starry UI 2.0 — DESIGN.md

> **Geely ToB Mobile Design System**
> 支持多品牌切换的设计系统文档，供 AI 代理生成一致的 UI。

---

## 概述

本项目提供 GDS Starry 2.0 设计系统的 DESIGN.md 文件，支持以下品牌：

| 品牌 | 英文代号 | 模式名称 |
|------|----------|----------|
| 极氪 | `zeekr` | `Z_Brand` |
| 领克 | `lynkco` | `L_Brand` |
| 售后 | `after-sales` | `A_Brand` |

---

## 使用方法

### 1. 直接使用

将 `DESIGN.md` 复制到项目根目录，AI 代理即可读取并生成符合设计规范的 UI。

### 2. 指定品牌

在指令中明确指定品牌：

```
使用 DESIGN.md，品牌模式为 Z_Brand（极氪），生成一个列表页面...
```

### 3. 配置文件切换

在项目中创建 `.starryrc` 文件：

```json
{
  "brand": "zeekr",
  "brandMode": "Z_Brand"
}
```

---

## 在线预览

访问 [GitHub Pages](https://your-username.github.io/GDS-starryUI-design-md/) 查看设计系统预览。

---

## 文件结构

```
GDS-starryUI-design-md/
├── README.md                    # 项目说明
├── DESIGN.md                    # 主设计文档（包含品牌切换逻辑）
├── brands/
│   ├── zeekr.md                 # 极氪品牌变量
│   ├── lynkco.md                # 领克品牌变量
│   └── after-sales.md           # 售后品牌变量
├── preview/
│   ├── index.html               # 预览主页面
│   ├── styles.css               # 预览页样式
│   └── scripts.js               # 品牌切换逻辑
└── components/
    ├── button.md                # Button 组件规范
    ├── navigation-bar.md        # Navigation Bar 组件规范
    └── tabs.md                  # Tabs 组件规范
```

---

## 设计系统来源

- **Figma 文件**: [GDS Starry 2.0](https://www.figma.com/design/F05obr0jxc9r2iv6P7Q9pt)
- **文件 Key**: `F05obr0jxc9r2iv6P7Q9pt`

---

## 版本信息

- **版本**: 2.0
- **更新日期**: 2026-04-09
- **维护团队**: GDS Design Team

---

## License

MIT License