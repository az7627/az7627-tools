# AZ7627 Tools

[简体中文（中国大陆）](README.md) / English (US)

A tools navigation portal for AZ7627, bringing together CS2 broadcast HUD, live streaming, guessing games, and more.

## Included Projects

| Subproject | Description | Stack |
|-----------|-------------|-------|
| [cs2-hud-matchless](https://github.com/az7627/cs2-hud-matchless) | CS2 match HUD toolkit with real-time map BP and static broadcast pages | Python Flask + Socket.IO |
| [live-stream-web](https://github.com/az7627/live-stream-web) | Self-hosted live streaming platform (RTMP/HLS + danmaku) | Python FastAPI + Node.js |
| [guess-cs2-players](https://github.com/az7627/guess-cs2-players) | Real-time multiplayer CS2 pro player guessing game | Node.js Express + Socket.IO |

## Deployment

This repository uses git submodules. Clone with:

```bash
git clone --recurse-submodules https://github.com/az7627/az7627-tools.git
```

See each subproject's README for deployment details.

## License

MIT License
