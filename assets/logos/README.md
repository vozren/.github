# Vozren Logo

所有 SVG 均为透明背景的矢量路径，不依赖外部字体或图片。横版统一采用左侧 V/Z 图标、右侧企业名称；中文名称为「沃兹伦科技」，英文名称为「vozren」。

`-dark` 表示适配深色背景，图形与文字使用浅色；无此后缀的版本适配浅色背景。

| 用途 | 浅色背景 | 深色背景 |
| --- | --- | --- |
| 英文横版 | [vozren-logo.svg](vozren-logo.svg) | [vozren-logo-dark.svg](vozren-logo-dark.svg) |
| 中文横版 | [vozren-logo-zh.svg](vozren-logo-zh.svg) | [vozren-logo-zh-dark.svg](vozren-logo-zh-dark.svg) |
| 纯图标 | [vozren-icon.svg](vozren-icon.svg) | [vozren-icon-dark.svg](vozren-icon-dark.svg) |

中文名称由等线 Light 字形转换为矢量轮廓；最终文件不包含字体文件，也不要求使用方安装字体。

## Favicon

- [favicon.ico](favicon.ico)：由完整的 [vozren-icon.svg](vozren-icon.svg) 直接导出，包含 16、24、32、48、64、128、256 像素的透明图像。
- [favicon.svg](favicon.svg)：与 [vozren-icon.svg](vozren-icon.svg) 完全一致，适用于支持 SVG favicon 的浏览器。

Favicon 沿用完整图标的形状、电路线条、节点及渐变；ICO 仅按目标尺寸缩放导出。

按网站实际部署路径调整以下地址：

```html
<link rel="icon" href="/assets/logos/favicon.ico" sizes="16x16 24x24 32x32 48x48 64x64 128x128 256x256">
<link rel="icon" href="/assets/logos/favicon.svg" type="image/svg+xml" sizes="any">
```
