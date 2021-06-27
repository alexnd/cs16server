# Counter-Strike 1.6 Server by Reactor Team

## Features

* Runs in docker container with zero configuration
* Default address is `0.0.0.0` ad port is `27015`
* AmxMod + Metamod + Podbots in the box

## Requirements to host and play

* [Docker](https://docs.docker.com/engine/install/ubuntu/)

* [Official Counter-Strike 1.6 client](https://store.steampowered.com/app/10/CounterStrike/)

## Setup

* Copy [this](https://github.com/alexnd/cs16server) repository to your work dir

* Run in your terminal `docker-compose up -d` in the root of `docker-compose.yaml`

## Monitor

* `docker-compose logs --follow hlds`

* `docker ps -a`


## Stop / Start

* `docker-compose stop hlds`

* `docker-compose start hlds`

## Enter interactive command shell

`docker-compose exec hlds /bin/bash`

## Config files

`server.cfg`

`banned.cfg`

`listip.cfg`

`addons/amxmodx/configs/cvars.ini`

`addons/amxmodx/configs/maps.ini`

...

`addons/podbot/podbot.cfg`

## Reinstall container

`docker-compose up -d --force-recreate`

---

* **Counter-Strike** - is registered trademark of **Valve** corporation