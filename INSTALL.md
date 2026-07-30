# IELTS Vocab App 安装指南

## iPhone / iPad
1. 将整个文件夹部署到支持 HTTPS 的静态网站。
2. 使用 Safari 打开网站。
3. 点击“分享”。
4. 选择“添加到主屏幕”。

## Android
1. 使用 Chrome 打开已部署的网站。
2. 点击浏览器菜单。
3. 选择“安装应用”或“添加到主屏幕”。

## 电脑本地预览
PWA 和 Service Worker 不能直接通过双击 `index.html` 完整运行，需要使用本地服务器。

例如安装 Python 后，在本文件夹内运行：

```bash
python3 -m http.server 8080
```

然后访问：

```text
http://localhost:8080
```
