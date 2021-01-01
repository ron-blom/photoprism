# PhotoPrism
This project is part of my [homeserver](https://github.com/ron-blom/homeserver) project and will deploy photoprism on my homeserver. 

persistent storage:
```
/photoprism/storage
/photoprism/originals
/photoprism/import

```

Images used in this project:
```
photoprism/photoprism:latest (https://hub.docker.com/r/photoprism/photoprism/)
```

### Deploy 

helm secrets upgrade --install photoprism-chart ./photoprism-chart -f photoprism-chart/secrets.yaml
