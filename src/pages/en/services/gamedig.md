---
title: GameDig
description: GameDig Widget Configuration
layout: ../../../layouts/MainLayout.astro
---

Uses the [GameDig](https://www.npmjs.com/package/gamedig) library to get game server information for any supported server type.

Allowed fields (limited to a max of 4): `["name", "map", "currentPlayers", "players", "maxPlayers", "bots", "ping"]`.

```yaml
widget:
    type: gamedig
    serverType: csgo # see https://github.com/gamedig/node-gamedig#games-list
    url: udp://server.host.or.ip:port
```

*Added in v0.6.24*
