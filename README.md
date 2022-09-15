<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

# Execute in development

1. clone the repository
2. execute

```
yarn install
```

3. you need have NestCLI installed

```
npm i -g @nestjs/cli
```

4. get up the database

```
docker-compose up -d
```

5. Clone file `.env.template` and rename the copy `.env`

6. add enviroment variables defined in `.env`

7. execute app in dev mode:

```
yarn start:dev
```

8. rebuild database with seed

```
http://localhost:3000/api/seed
```

## Used Stack

- MongoDB
- Nest

# Notes

Keroku redeploy sin cambios:

```
git commit --allow-empty -m "Tigger Heroku deploy"

git push heroku <master | main>
```
