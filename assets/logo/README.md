# Vozren Logo Assets

## 文件说明 · Files

### 主 Logo（带背景）
| 文件 | 说明 |
|------|------|
| `vozren-logo-v1.svg` | **方案 A** — 声波 V 字，紫蓝渐变圆角方块 |
| `vozren-logo-v2.svg` | **方案 B** — 声波圆环 + V 字，青蓝渐变圆角方块 |
| `vozren-logo-v3.svg` | **方案 C** — 几何电路 V 字，深色圆角方块 |

### 透明背景变体
| 文件 | 说明 |
|------|------|
| `vozren-logo-dark.svg` | 彩色 logo，透明底，适合浅色背景 |
| `vozren-logo-light.svg` | 纯白 logo，透明底，适合深色背景 |

### 横版组合
| 文件 | 说明 |
|------|------|
| `vozren-logo-horizontal.svg` | 图标 + 文字横排，深色文字 |
| `vozren-logo-horizontal-white.svg` | 图标 + 文字横排，白色文字 |

## 设计理念 · Design Concept

**核心元素：V + 声波**

- **V** = Vozren 首字母，也是 Voice（声音）的首字母
- **声波** = 呼应品牌名「用技术放大每一个声音」
- **圆角方块** = 友好、现代、可信赖

**品牌色：**
- 主色：`#6366F1` (Indigo)
- 辅色：`#8B5CF6` (Violet)
- 点缀：`#38BDF8` (Sky)
- 深色：`#1E293B` (Slate)

## 导出 PNG · Export

```bash
# 使用 rsvg-convert（需安装 librsvg）
rsvg-convert -w 512 -h 512 vozren-logo-v1.svg > vozren-logo-512.png
rsvg-convert -w 256 -h 256 vozren-logo-v1.svg > vozren-logo-256.png
rsvg-convert -w 128 -h 128 vozren-logo-v1.svg > vozren-logo-128.png

# 或使用 Inkscape
inkscape vozren-logo-v1.svg --export-filename=vozren-logo-512.png --export-width=512
```

## 使用建议 · Usage

- **GitHub 组织头像**：使用 `vozren-logo-v1.svg`（或任一方案）
- **README 顶部**：使用 `vozren-logo-horizontal.svg`
- **深色模式**：使用 `vozren-logo-light.svg` 或 `vozren-logo-horizontal-white.svg`
- **Favicon**：导出 32x32 或 64x64 PNG
