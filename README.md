# Special Telegram

This is just a really basic example of running a postgres container and a nodejs container in docker compose for development.

Run migrations with:

``` sh
docker compose run --rm nodejs npx prisma migrate dev
```

Then you can run the example query from the prisma docs:

``` sh
docker compose run --rm nodejs npx tsx index.ts
```
