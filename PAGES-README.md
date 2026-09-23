# TinyFangDianGames · 在线试玩

本分支（`gh-pages`）仅用于通过 GitHub Pages 提供**点开即玩**的静态托管，
不包含游戏源码的开发历史。

## 在线地址

- 首页：https://frankeyling.github.io/TinyFangDianGames/
- 🌍 世界（方块世界 v9）：https://frankeyling.github.io/TinyFangDianGames/chen.html
- 🧻 抽纸巾 · 完整版（简体中文）：https://frankeyling.github.io/TinyFangDianGames/paper-zh-full.html
- 📄 抽纸巾 · 简中版（V9）：https://frankeyling.github.io/TinyFangDianGames/paper-zh.html
- 🧻 抽纸巾 · 俄语原版：https://frankeyling.github.io/TinyFangDianGames/paper-ru.html

## 本分支文件

| 文件 | 来源分支 / 提交 | 说明 |
| --- | --- | --- |
| `index.html` | 本分支新增 | 试玩导航首页 |
| `chen.html` | `fix/chen-bugs` @ `abd95ba` | 方块世界 v9（含三处缺陷修复） |
| `paper-zh-full.html` | 由 `paper-ru.html` 汉化 | 抽纸巾完整版 · 简体中文 |
| `paper-zh.html` | `031e260` | 抽纸巾简中 V9 版 |
| `paper-ru.html` | `main` @ `f3e75c7` | 抽纸巾完整版 · 俄语原文 |

四个游戏文件均为**单文件纯前端实现**，无外部依赖，可离线运行。

### 汉化说明

`paper-zh-full.html` 由 `paper-ru.html` 逐条汉化而来：仅替换界面与数据
文案（398 条字符串），游戏逻辑、数值、函数结构完全保持原样。

- 存档键由 `paperRUV1` 改为 `paperZHCN1`，避免与俄语版在同一域名下
  互相覆盖存档
- `lang` 属性由 `ru` 改为 `zh-CN`

## 游戏源码与完整提交历史

| 分支 | 内容 |
| --- | --- |
| `main` | 纸巾系列，`纸巾.html` 的演进历史 |
| `block-world` | 方块世界 v1 → v9 的完整演进历史 |
| `fix/chen-bugs` | 方块世界 v9 的缺陷修复（从 `block-world` 分出） |

## 许可

基于 [MIT License](LICENSE) 开源，游戏代码作者 KaZhe。
