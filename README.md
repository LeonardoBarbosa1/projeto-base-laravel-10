## Para iniciar com esse projeto você precisar ter instalado e configurado o docker em sua máquina.

### Inicie os containers 
    - docker compose up -d
### Atualize o composer
    -  docker compose run --rm laravel.test composer update
### Execute a migration
    - docker compose run --rm localhost.test php artisan migrate
### Rode o npm
    - npm install
    - npm run dev

