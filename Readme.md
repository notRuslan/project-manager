#### Deploy to registry
```
REGISTRY_ADDRESS=REGISTRY_IP IMAGE_TAG=0 make build-production
```

docker-compose run --rm manager-php-cli composer require slim/slim

docker-compose run --rm manager-php-cli composer install --no-dev
