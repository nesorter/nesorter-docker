# nesorter-docker
### Репо с docker-compose.yml для blazing-fast развёртывания и использования nesorter

- Описания переменных env: [туточки](https://github.com/nesorter/nesorter/tree/main#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5-env-%D0%B4%D0%BB%D1%8F-%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA%D0%B0-%D0%B2-docker-%D0%B8-%D0%B5%D1%81%D0%BB%D0%B8-%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA-%D0%BF%D0%BB%D0%B0%D0%BD%D0%B8%D1%80%D1%83%D0%B5%D1%82%D1%81%D1%8F-%D0%BD%D0%B5-%D0%B2-docker)

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
