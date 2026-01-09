# 🎵 音频文件放置说明

## 📁 在这里放置音频文件

请在 `public/` 目录下创建 `sounds/` 文件夹，并放入以下音频文件：

```
public/
└── sounds/                    ← 需要创建这个文件夹
    ├── bg-loop.mp3           ← 背景音乐
    ├── click-hovering.mp3    ← 点击音效
    └── success-match.mp3     ← 配对成功音效
```

---

## 🚀 快速创建 sounds 文件夹

### Windows (PowerShell)
```powershell
# 在项目根目录执行
New-Item -Path "public\sounds" -ItemType Directory -Force
```

### Mac / Linux / Git Bash
```bash
# 在项目根目录执行
mkdir -p public/sounds
```

---

## 📋 文件清单

| 文件名 | 类型 | 格式 | 说明 |
|--------|------|------|------|
| `bg-loop.mp3` | 必需 | mp3/wav | 背景音乐（循环播放） |
| `click-hovering.mp3` | 必需 | mp3/wav | 点击卡牌音效 |
| `success-match.mp3` | 必需 | mp3/wav | 配对成功音效 |

---

## ✅ 重要说明

### 文件名必须完全匹配
- ❌ `bg_loop.mp3` - 错误（下划线）
- ❌ `BG-Loop.mp3` - 错误（大小写）
- ✅ `bg-loop.mp3` - 正确
- ✅ `bg-loop.wav` - 正确（格式可以不同）

### 没有音频文件？
**完全没问题！** 游戏会自动检测：
- 有音频 → 自动启用音效
- 无音频 → 静默运行，游戏正常进行

---

## 📖 详细指南

更多信息请查看：
- [AUDIO_GUIDE.md](../AUDIO_GUIDE.md) - 完整音效配置指南
- [QUICK_START.md](../QUICK_START.md) - 快速开始

---

**创建完成后，直接运行游戏即可！** 🎮
