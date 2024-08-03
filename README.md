# README

## local dev

```sh
docker build -f Dockerfile-chainguard -t comfyui .
docker run -it --entrypoint /bin/bash comfyui
```

## remote dev

```sh
docker run -it --entrypoint /bin/bash jahanson/comfyui:latest
```