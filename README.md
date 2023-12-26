## Para iniciar com esse projeto você precisar ter instalado e configurado o docker em sua máquina.

### Inicie os containers

```bash
docker compose up -d
```
### Rode comandos
```bash
docker-compose exec laravel.test composer update

cp .env.example .env
docker-compose exec laravel.test php artisan key:generate
docker-compose exec laravel.test php artisan serve

sail down -v
docker compose up -d
```
### Execute a migration
```bash
docker-compose exec localhost.test php artisan migrate
```
### Rode o npm
```bash
npm install
npm run dev
```

