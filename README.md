# ADempiere Base

<p align="center">
  <a href="https://adoptium.net/es/temurin/releases/?version=11">
    <img src="https://badgen.net/badge/Java/11/orange" alt="Java">
  </a>
  </a>
  <a href="https://github.com/adempiere/zk-ui/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-GNU/GPL%20(v2)-blue" alt="License">
  </a>
  <a href="https://github.com/adempiere/zk-ui/releases/latest">
    <img src="https://img.shields.io/github/release/adempiere/zk-ui.svg" alt="GitHub release">
  </a>
</p>

![image](https://github.com/JesusAlbujas/adempiere-base/assets/134967453/a7083320-31d4-4a0b-b4b9-dc50e6dd9b12)

This repository is based on the official [adempiere zk](https://github.com/adempiere/zk-ui) repository. Using Jetty as a web server and ADempiere in version 3.9.4.

### Requirements

- [Docker Compose v2.16.0 or later](https://docs.docker.com/compose/install/linux/)

```Shell
- docker compose version
Docker Compose version v2.16.0
```

## Run it

1. Just go to `docker-compose` folder and run it

```Shell
cd docker-compose
```

2. Build and up

```Shell
docker compose build && docker compose up
```