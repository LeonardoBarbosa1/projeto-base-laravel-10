## Para iniciar com esse projeto você precisar ter instalado e configurado o docker em sua máquina.

### Inicie os containers

```bash
docker compose up -d
```
### Rode comandos
```bash

docker-compose exec laravel.test composer update

```
```bash

cp .env.example .env

docker-compose exec laravel.test php artisan key:generate

```
### Execute a migration
```bash
docker-compose exec laravel.test php artisan migrate
```
### Rode o npm
```bash
npm install
npm run dev
```

### Caso não inicie o mysql rode 
```bash
sail down -v
docker compose up -d
```
