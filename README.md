# RotoServer

This is the RotoServer configuration, powered by
[Docker Minecraft Server](https://docker-minecraft-server.readthedocs.io/en/latest/).

## Pre-requisites

- UNIX environment (Linux / WSL)
- Docker installed + daemon running

> [!TIP]
> To make the server reachable from outside the local network, use a *dynamic DNS*
> like [Duck DNS](https://www.duckdns.org/install.jsp).

## Quick start

1. Clone this repo
2. Place the MC world in `minecraft/world`
3. Run the server with Docker


```bash
cd rotoserver
docker compose up -d

```
