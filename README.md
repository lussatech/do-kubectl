# DO-Kubectl
---

![MicroBadger Size](https://img.shields.io/microbadger/image-size/image-size/lussatech/do-kubectl.svg)

Is a enviroments for deploy container on kubernetes cluster in digital ocean environments

## Build

```bash
docker build . -t do-kubectl
```

## Deploy

```bash
docker tag do-kubectl new-repo:tagname
docker push new-repo:tagname
```