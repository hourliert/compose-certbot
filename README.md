# compose-certbot

Creates letsencrypt certificate

## Getting started

### Free the 80 and 443 ports

```
docker stop nginx-proxy
```

### Edit configuration
Create a `.env` file with the according variables used in `docker-compose.yml`

### Run
Execute `docker-compose run certbot --service-ports`.

You could override this compose file by using [this](https://docs.docker.com/compose/extends/).
