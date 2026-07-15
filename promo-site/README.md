# Tiptrip 宣传网页

项目包含三套独立宣传页。三套页面使用同一份 Tiptrip 文案与功能信息，视觉方向和动效表达不同。

## 本地预览

在项目根目录启动静态服务：

```powershell
python -m http.server 4173
```

页面地址：

- 第一版：`http://localhost:4173/promo-site/index.html`
- 第二版：`http://localhost:4173/promo-site/index-v2.html`
- 第三版：`http://localhost:4173/promo-site/index-v3.html`

## 文件

- `index.html`：第一版宣传页
- `index-v2.html`：基于第一版文案制作的布局与动画增强版
- `index-v3.html`：基于 Hermes Agent 视觉 DNA 制作的钴蓝编辑风格版
- `design-dna.json`：Roadster 参考站的设计 DNA
- `design-dna-hermes.json`：Hermes Agent 参考站的三维设计 DNA
- `assets/tiptrip-icon.png`：Tiptrip 应用图标

APK 下载链接指向项目中的现有构建产物：`build/app-v191/outputs/apk/debug/app-debug.apk`。
