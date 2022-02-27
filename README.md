# 1on1app
1on1を管理するアプリケーション

## Get Started

```bash
docker-compose build
docker-compose up -d

docker-compose exec -T app cp .env.example .env
docker-compose exec -T app php artisan key:generate
docker-compose exec -T app php artisan config:clear
```

http://localhost:8080/