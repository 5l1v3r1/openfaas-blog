# OpenFaaS Blog

Using:
  * Hugo
  * Casper Theme

## Build

```
docker run --rm -ti -v $(pwd):$(pwd) -w $(pwd) andthensome/alpine-hugo-git-bash hugo
```

This will create the site inside the ```public``` directory.

## Server

```
docker run --rm -it -v $(pwd):$(pwd) -p 1313:1313 -w $(pwd) andthensome/alpine-hugo-git-bash hugo --bind=0.0.0.0 server
```
