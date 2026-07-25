# AZ7627 Tools

简体中文（中国大陆） / [English (US)](README_en_US.md)

AZ7627 的工具导航门户，汇集 CS2 广播 HUD、实时直播、竞猜游戏等小工具。

## 包含项目

| 子项目 | 描述 | 技术栈 |
|--------|------|--------|
| [cs2-hud-matchless](https://github.com/az7627/cs2-hud-matchless) | CS2 比赛 HUD 工具包，含实时地图 BP 和静态广播页面 | Python Flask + Socket.IO |
| [live-stream-web](https://github.com/az7627/live-stream-web) | 自建直播平台（RTMP/HLS + 弹幕） | Python FastAPI + Node.js |
| [guess-cs2-players](https://github.com/az7627/guess-cs2-players) | 实时多人 CS2 职业选手竞猜游戏 | Node.js Express + Socket.IO |

## 部署

本仓库使用 git submodule 管理子项目。克隆时使用：

```bash
git clone --recurse-submodules https://github.com/az7627/az7627-tools.git
```

部署详情请参阅各子项目的 README。

## 许可

MIT License
