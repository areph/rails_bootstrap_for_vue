# README

## Rails6.0 & Webpacker & Vue on Docker

### Setup
```
docker-compose run --rm web bundle install
docker-compose run --rm web rails webpacker:install
docker-compose run --rm web rails db:create
```

### JSコンパイル

```
docker-compose run --rm web bin/webpack-dev-server
```