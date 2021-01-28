# nexus

... with Docker Compose and Serverless.

## New

```
$ docker-compose up
```

or

```
# Use VS Code Remote Container
```

## Old
Setup and start postgres
```
$ docker run --detach --publish 5432:5432 -e POSTGRES_PASSWORD=postgres --name nexus-tutorial-postgres postgres:10
$ npx prisma migrate dev --preview-feature
```

start postgres
```
$ docker start nexus-tutorial-postgres
```

```
npm run dev
```