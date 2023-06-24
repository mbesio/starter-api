## Starter kit for api

Setups a hello world api using express, prisma and a postgres database.

It comes with configuration files such as. gitignore, and .prettierrc to be customized

Standard npm scripts to run api in dev mode, build, and start in production are also provided.

Requires to setup a database either locally or hosted. Run the prisma migrate command to sync the schemas.

### To get started

- Install dependencies

```
npm i
```

- Prisma is already initialized, so no need to run the following command:

```
npx prisma init
```

- Add Database url in .env file
- Define your schema in prisma/schema.prisma and sync with database

```
npx prisma migrate dev --name init
```

- Start the app and develop using nodemon:

```
npm run dev
```
