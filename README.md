# 抽纸巾 · TinyFangDianGames

一个单文件、纯前端的**抽纸巾增量放置（Incremental / Idle）小游戏**。无需构建、无需服务器，双击 `纸巾.html` 即可开始游玩。

## ▶️ 在线试玩

不想下载？点这里直接玩：**https://frankeyling.github.io/TinyFangDianGames/**

试玩页同时收录了方块世界与两个纸巾版本。

## 👤 作者

本项目全部代码与设计均由 **KaZhe** 完成，版权归 KaZhe 所有。

> 仓库目前仅由 FrankeyLing 代为托管于 GitHub，FrankeyLing 未参与本项目的任何开发工作。

## ✨ 玩法特色

| 模块 | 说明 |
| --- | --- |
| 🧻 抽纸巾 | 点击抽纸巾，按稀有度随机出货，图鉴共 21 个稀有度档位 |
| 📖 纸巾图鉴 | 记录已收集到的纸巾种类与数量 |
| 📦 纸巾仓库 | 有容量上限，可升级扩容 |
| 🔄 资源转换台 | 把纸巾/材料按比例兑换成金币等资源 |
| 🏭 建筑升级 | 消耗材料升级工厂，提升每秒自动产出 |
| ⬆️ 升级商店 | 消耗金币提升点击收益、出货幸运、售价与自动产出 |
| ✨ 升华转生 | 转生获得升华点，兑换永久加成（产出、金币、材料、暴击） |
| ⚙️ 全局调节 | 可调节游戏速度倍率与售价倍率，方便测试 |
| 🏆 成就 | 达成条件自动获得奖励 |
| 📊 全局统计 | 累计纸巾 / 材料 / 金币 / 转生次数一览 |

其它细节：

- **离线收益**：离开一段时间后可领取离线产出。
- **本地存档**：使用 `localStorage` 自动/手动存档，支持读档与全部重置。
- **移动端友好**：响应式布局，按钮触控区域 ≥ 44px。

## 🚀 快速开始

```bash
git clone https://github.com/FrankeyLing/TinyFangDianGames.git
cd TinyFangDianGames
```

然后直接用浏览器打开 `纸巾.html` 即可：

```bash
# Linux
xdg-open 纸巾.html
# macOS
open 纸巾.html
# Windows
start 纸巾.html
```

如果你更习惯 HTTP 方式访问，也可以起一个静态服务器：

```bash
python3 -m http.server 8000
# 浏览器访问 http://localhost:8000/纸巾.html
```

## 🛠️ 技术说明

- 纯 **HTML + CSS + 原生 JavaScript**，全部逻辑集中在单个 `纸巾.html` 文件内。
- 无第三方依赖、无打包步骤、无网络请求，可完全离线运行。
- 存档 key 保存在浏览器 `localStorage` 中，清理浏览器数据会丢失存档。

## 📄 开源许可

本项目基于 [MIT License](LICENSE) 开源，Copyright (c) 2026 KaZhe。
