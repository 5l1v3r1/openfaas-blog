# OpenFaaS Blog

Using:
  * Hugo
  * Casper Theme

Build

```
docker run --rm -ti -v $(pwd):$(pwd) -w $(pwd) giantswarm/hugo
```

This will create the site inside the ```public``` directory.

Serve

```
docker run --rm -ti -v $(pwd):$(pwd) -p 1313:1313 -w $(pwd) giantswarm/hugo server
```
