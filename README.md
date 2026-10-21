# ChinAI3 · Windows 版 介绍页

<https://lugui906.github.io/aaimw/>

ChinAI3 Windows 移植版的单文件落地页。版式与配色参考
<https://lugui906.github.io/chinai3w/>，内容取自 `~/chinai3-win`：
WebView2 外壳、`aim.exe` 引擎、截图认字、桌面控制、长期记忆、日程与离线安装。

## 页面内容

- 四个内置应用：AI 助手 / 桌面控制 / 自动化 / 日程
- 12 项能力：截图认字、窗口上下文、文件上传、朗读、AI 记忆、活动记录、模型与 Key、多会话、历史收藏…
- 移植对照：GTK4 → WebView2、`aim` → `aim.exe`、AT-SPI → Win32 + pyautogui、SAPI、`taskkill`…
- 场景演示、安装步骤、静默安装命令与发行规格表

页面还包含：

- 真实界面截图（演示对话）与「移植对照」终端示意
- Open Graph / Twitter 分享卡片（`og.png`）、JSON-LD 结构化数据
- 同风格的 404 页、`robots.txt` 与 `sitemap.xml`

## 结构

```
index.html    单文件页面（内联 CSS / JavaScript / SVG 图标）
chinai3.png   应用图标，同时用作 favicon
ui.png        主界面截图（演示对话，来自同一套 Web UI）
og.png        1200 × 630 社交分享卡片
404.html      同风格 404
robots.txt    抓取规则
sitemap.xml   站点地图
.nojekyll     关闭 Jekyll，直接静态托管
```

无构建步骤、无外部依赖。本地预览：

```bash
python3 -m http.server -d . 8000
# http://127.0.0.1:8000
```

## 安装包

安装包体积超过 GitHub 单文件 100 MB 限制，统一放在中国移动云盘（无提取码）：

<https://yun.139.com/shareweb/#/w/i/2ygbaWBcT140h>

- `chinai3-1.0.0-x64.msi`：按用户安装，免管理员
- `chinai3-win-1.0.0.zip`：免安装包，解压即用

## Pages

`main` 分支根目录，经典 GitHub Pages 构建（Deploy from a branch）。
