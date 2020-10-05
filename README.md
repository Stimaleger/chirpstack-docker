# ChirpStack Docker

This repository contains a skeleton to setup the [ChirpStack](https://www.chirpstack.io)
open-source LoRaWAN Network Server stack using [Docker Compose](https://docs.docker.com/compose/).

## Architecture

![Alt text](./images/archi.jpg?raw=true "Architecture")

## Requirements

Before using this `docker-compose.yml` file, make sure you have [Docker](https://www.docker.com/community-edition)
installed.

## Usage

1 - Precise volumes location in ```docker-compose.yml``` file.

3 - Run docker (Option d is for detach mode): 

```bash
docker-compose up -d 
```
