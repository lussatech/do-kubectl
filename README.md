# DO-Kubectl

![Docker Pulls](https://img.shields.io/docker/pulls/lussatech/do-kubectl.svg)

Is an enviroments for deploy container on digitalocean kubernetes cluster

## Build

```bash
docker build . -t do-kubectl
```

## Deploy

```bash
docker tag do-kubectl new-repo:tagname
docker push new-repo:tagname
```