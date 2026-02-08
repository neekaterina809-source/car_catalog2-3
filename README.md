# car_catalog

## Запуск с Docker

1. Установи Docker   Desktop
2. В корне проекта выполни:

```bash
docker-compose up -d
```

3. Открой http://localhost:8080

Параметры подключения:
- System: PostgreSQL
- Server: db
- Username: postgres
- Password: postgres
- Database: car_catalog_db

## Исследование

```sql
SELECT color, AVG(price) FROM cars GROUP BY color;
```

```sql
SELECT brand, COUNT(*) FROM cars GROUP BY brand;
```


