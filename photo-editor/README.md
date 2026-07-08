# 证件照 H5 编辑工具

这是从 Git 历史版本 `629cf0c` 导出的 H5 静态版，包含：

- 智能人像抠图。
- 背景色替换。
- 边缘保留。
- 边缘柔化。
- 多种证件照尺寸。
- JPEG/JPG/PNG/BMP/TIFF 导出。

## 本地打开

直接打开：

```text
photo-editor/index.html
```

## GitHub Pages 部署

如果当前仓库已经启用 GitHub Pages，推送后访问：

```text
https://你的用户名.github.io/photo-editor/
```

## 注意

页面依赖 CDN：

- CropperJS
- MediaPipe Selfie Segmentation

如果网络无法访问 CDN，裁剪或智能抠图会加载失败。
