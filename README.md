
# Dockerized tools

On this repo I have Dockerfiles for some tools that are not dockerized. This is the case for some really old tools and tools with mantainers rejeckting Dockerization on the main repo.

## Tools

### sqlmap

Build with:

```shell
docker build -t sqlmap 'https://github.com/luastan/dockerized-tools.git#sqlmap'
```

Run with:

```shell
docker run --rm -it sqlmap --help
```

### LiferayScan

```shell
docker build -t liferayscan 'https://github.com/luastan/dockerized-tools.git#liferayscan'
```

Run with:

```shell
docker run --rm -it liferayscan -h
```