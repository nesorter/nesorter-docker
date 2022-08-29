# nesorter-docker
### Репо с docker-compose.yml для blazing-fast развёртывания и использования nesorter

## How to

- Первое:
```sh
wget "https://github.com/nesorter/nesorter-docker/archive/refs/heads/main.zip" && \
unzip main.zip && \
cd nesorter-docker-main && \
docker-compose pull
```

- Второе: поправить ENV'ы в docker-compose.yml на своё усмотрение

- Третье:
```sh
docker-compose up # ключ -d для демонизации и автостарта с системой
```
