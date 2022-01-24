## Setup

Requirements:

- Docker
- Docker Compose



```bash
docker-compose run --rm -v $HOME/.cache/composer:/tmp -e COMPOSER_HOME=/tmp php composer install
docker-compose run --rm node npm install
```

docker-compose up -d
```
