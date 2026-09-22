# Vozren Logo

所有 SVG 均为透明背景的矢量路径，不依赖外部字体或图片。横版统一采用左侧 V/Z 图标、右侧企业名称；中文名称为「沃兹伦科技」，英文名称为「vozren」。

`-dark` 表示适配深色背景，图形与文字使用浅色；无此后缀的版本适配浅色背景。

| 用途 | 浅色背景 | 深色背景 |
| --- | --- | --- |
| 英文横版 | [vozren-logo.svg](vozren-logo.svg) | [vozren-logo-dark.svg](vozren-logo-dark.svg) |
| 中文横版 | [vozren-logo-zh.svg](vozren-logo-zh.svg) | [vozren-logo-zh-dark.svg](vozren-logo-zh-dark.svg) |
| 纯图标 | [vozren-icon.svg](vozren-icon.svg) | [vozren-icon-dark.svg](vozren-icon-dark.svg) |

中文名称由等线 Light 字形转换为矢量轮廓；最终文件不包含字体文件，也不要求使用方安装字体。

## GitHub 组织头像

[vozren-github-avatar.png](vozren-github-avatar.png)：512 × 512 像素、白色背景的 PNG，可直接用于 GitHub 组织头像上传。由已确认的 [vozren-icon.svg](vozren-icon.svg) 导出，保留完整图标及蓝色渐变，不含企业名称。

## Favicon

- [favicon.ico](favicon.ico)：包含针对标签页优化的 16、32、48 像素图像。
- [favicon-32.png](favicon-32.png)：32 × 32 像素的浏览器标签页图标。
- [apple-touch-icon.png](apple-touch-icon.png)：180 × 180 像素的 Apple Touch Icon。
- [favicon.svg](favicon.svg)：基于 [vozren-icon.svg](vozren-icon.svg) 的 favicon 专用版本。

Favicon 保留原始 V/Z 图形、电路线条、节点及渐变，并增加白色圆角底和浅灰描边，以便在深浅色浏览器标签栏中保持稳定对比度。16、32、48 像素版本对原有描边进行了小尺寸光学校正；完整品牌图标本身不受影响。

按网站实际部署路径调整以下地址：

```html
<link rel="icon" href="/assets/logos/favicon-32.png" type="image/png" sizes="32x32">
<link rel="icon" href="/assets/logos/favicon.ico" sizes="16x16 32x32 48x48">
<link rel="apple-touch-icon" href="/assets/logos/apple-touch-icon.png" sizes="180x180">
```
