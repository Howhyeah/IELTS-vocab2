# IELTS Vocab App

这是一个雅思词汇学习 PWA 基础项目。

## 文件结构

- `index.html`：PWA 主页面
- `manifest.json`：应用名称、图标和显示方式配置
- `sw.js`：离线缓存
- `icon-192.png`：192×192 应用图标
- `icon-512.png`：512×512 高清应用图标
- `INSTALL.md`：安装与本地预览指南
- `data/`：词汇数据目录

## 数据文件

每个 JSON 文件使用以下基础结构：

```json
{
  "version": "1.0",
  "category": "模块名称",
  "items": []
}
```

后续可在 `items` 数组中添加正式词汇数据。
