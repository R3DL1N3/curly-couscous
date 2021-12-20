# curly-couscous

## Docker in Docker

### Rocker
```bash
docker run -e PASSWORD=rocker -p 8787:8787 -v /var/run/docker.sock:/var/run/docker.sock rocker/tidyverse
```
