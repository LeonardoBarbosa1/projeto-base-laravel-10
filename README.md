## Para iniciar com esse projeto você precisar ter instalado e configurado o docker em sua máquina.

### Inicie os containers 
    - docker compose up -d
### Atualize o composer
    -  docker compose run --rm projeto-base-laravel-10-laravel.teste1 composer update
### Execute a migration
    - docker compose run --rm videocast.localhost php yii migrate
### Rode o npm
    - npm install
    - npm run dev

