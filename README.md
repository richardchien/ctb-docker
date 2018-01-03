# ctb-docker

[![Build Status](https://travis-ci.org/richardchien/ctb-docker.svg)](https://travis-ci.org/richardchien/ctb-docker)
[![Docker Repository](https://img.shields.io/badge/docker-richardchien/ctb-blue.svg)](https://hub.docker.com/r/richardchien/ctb/)
[![Docker Pulls](https://img.shields.io/docker/pulls/richardchien/ctb.svg)](https://hub.docker.com/r/richardchien/ctb/)

[jqqqqqqqqqq/coolq-telegram-bot](https://github.com/jqqqqqqqqqq/coolq-telegram-bot)（以下简称 CTB）的 Docker 镜像。

建议使用 Docker Compose 部署，Compose 文件参考 [docker-compose.yml](docker-compose.yml)。如果使用 Docker 分别启动容器的话，需要配置好容器的网络，否则酷 Q 和 CTB 容器可能无法互连。

CTB 的配置请参考它的 [README](https://github.com/jqqqqqqqqqq/coolq-telegram-bot/blob/master/README-zh_CN.md)。
