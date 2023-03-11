# nesorter-docker
### Repo with docker-compose.yml for blazing-fast deployment nesorter on linux systems with pulseaudio

- env variables descriptions: [at the end of README](https://github.com/nesorter/nesorter/blob/main/README.md#description-of-env)
## How to

- First:
```sh
wget "https://github.com/nesorter/nesorter-docker/archive/refs/heads/main.zip" && \
unzip main.zip && \
cd nesorter-docker-main && \
docker-compose pull
```

- Second: tune ENV's at docker-compose.yml

- Third:
```sh
docker-compose up # dont use -d key, thats broke pulseaudio sockets
```
