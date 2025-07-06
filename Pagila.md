### Pagila schema command docker
```
docker exec -i postgres psql -U admin -d pagila < data/pagila/pagila-schema.sql
```

### Pagila docker data command
```
docker exec -i postgres psql -U admin -d pagila < data/pagila/pagila-data.sql
```