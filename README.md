# Aaim · Windows 版介绍页

Aaim 的单页介绍站：常驻桌面的 AI 助手，用 MCP + Shell + GUI + API 多层控制代替大部分重复软件操作。

- 页面：<https://lugui906.github.io/aaimw/>
- 仓库：<https://github.com/lugui906/aaimw>

## 内容

- 首屏定位、能替你做什么、四层控制、快 / 省 / 轻、隐私说明
- 真实界面示意（演示对话）
- 分卷下载、密码与「Aaim1.zip → Aaim.z01」改名提示
- 三步安装说明
- Open Graph / Twitter 分享卡片、JSON-LD、404、robots、sitemap

## 下载

安装包分两个分卷，两个都要下载：

| 分卷 | 文件 | 密码 | 下载 |
|---|---|---|---|
| 1 | `Aaim1.zip` → 改名为 `Aaim.z01` | `5adm` | <https://wwaye.lanzoue.com/inYS24cw1k3i> |
| 2 | `Aaim2.zip`（保持原名） | `40oa` | <https://wwaye.lanzoue.com/ixyAL4cw0dre> |

两个文件放在同一文件夹，把 `Aaim1.zip` 重命名为 `Aaim.z01`，再解压 `Aaim2.zip`，得到 `aaim-1.0.0-x64.msi`。

## 结构

```
index.html    单文件页面（内联 CSS / JavaScript / SVG 图标）
aaim.png      应用图标，同时用作 favicon
ui.png        主界面截图（演示对话）
og.png        1200 × 630 社交分享卡片
404.html      同风格 404
robots.txt    抓取规则
sitemap.xml   站点地图
.nojekyll     关闭 Jekyll，直接静态托管
```

直接用浏览器打开 `index.html` 即可预览，或在本目录运行 `python3 -m http.server`。
