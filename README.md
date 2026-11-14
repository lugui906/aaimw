# Aaim · Windows 版（全网统一版）

Aaim 的单页介绍站：常驻桌面的 AI 助手，用 MCP + Shell + GUI + API 多层控制代替大部分重复软件操作。
这一版是**全网统一版**，同时给出 Windows / Linux / 安卓三个平台的入口。

- 页面：<https://lugui906.github.io/aaimw/>
- 仓库：<https://github.com/lugui906/aaimw>
- Linux 版页面：<https://lugui906.github.io/aaiml/>
- 安卓版页面：<https://lugui906.github.io/aaima/>

## 内容

- 首屏定位、能替你做什么、四层控制、快 / 省 / 轻、隐私说明
- 真实界面示意（新版界面实拍）
- 分卷下载、密码与「aaim-11.14-2.zip → aaim-11.14.z01」改名提示
- 三步安装说明、移动云盘备用通道
- Open Graph / Twitter 分享卡片、JSON-LD、404、robots、sitemap

## 下载（Windows）

**主通道：中国移动云盘，单个完整 MSI，无需解压、无需改名、没有提取码**

| 文件 | 大小 | 下载 |
|---|---|---|
| `aaim-1.0.0-x64_20261115_003018.msi` | 185.02 MB | <https://yun.139.com/shareweb/#/w/i/2yA8G1nZmxRxh> |

下载后直接双击安装（SmartScreen 提示「未知发布者」时选「更多信息 → 仍要运行」）。
按当前用户安装，不需要管理员权限。

**备用通道：蓝奏云，同一个 MSI 拆成两个分卷**（云盘打不开时用）

| 类型 | 文件 | 密码 | 大小 | 下载 |
|---|---|---|---|---|
| 主文件 | `aaim-11.14.zip`（保持原名） | `7fq9` | 86.0 MB | <https://wwaye.lanzoue.com/i7efE4fv3buf> |
| 分卷 | `aaim-11.14-2.zip` → 改名为 `aaim-11.14.z01` | `ghur` | 99.0 MB | <https://wwaye.lanzoue.com/iohCZ4fv3dna> |

两个文件放在同一文件夹，把 `aaim-11.14-2.zip` 重命名为 `aaim-11.14.z01`，再解压 `aaim-11.14.zip`。

## 结构

```
index.html    单文件页面（内联 CSS / JavaScript / SVG 图标）
aaim.png      应用图标，同时用作 favicon
ui.png        主界面截图 1440×900
og.png        1200×630 社交分享卡片
404.html      同风格 404
robots.txt    抓取规则
sitemap.xml   站点地图
.nojekyll     关闭 Jekyll，直接静态托管
```

直接用浏览器打开 `index.html` 即可预览，或在本目录运行 `python3 -m http.server`。
