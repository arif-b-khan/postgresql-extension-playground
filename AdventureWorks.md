### Adventure Works Schema

```
docker exec -i postgres psql -U admin -d adventureworks < data/adventureworks/adventureworks-schema.sql
```

### Adventure Works Data
```
docker exec -i postgres psql -U admin -d adventureworks < data/adventureworks/adventureworks-data.sql
```