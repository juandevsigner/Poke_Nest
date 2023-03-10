# Run development

1. Clone respository

2. Run

```
yarn install
```

3. You must install CLI

```
npm i -g @nestjs/cli
```

4. Run DB

```
docker-compose up -d
```

5. Clone file **.env.template** and rename it to **.env**

6. Exec Proyect

```
yarn start:dev
```

7. Build DB with data seed

```
http://localhost:3000/api/v2/seed
```

# Stack use

- MongoDB
- Nest
- Docker
- Typescript

# Production Build

1. Create **.env.prod**

2. Set env variables for production

3. Create new image

```
docker-compose -f docker-compose.prod.yaml --env-file .env.prod up --build
```

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>
