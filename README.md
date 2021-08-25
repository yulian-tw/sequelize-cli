# SEQUELIZE CLI

This is a repo to explore sequelize-cli functions, with Postgres Database.

## Set up

We will use `npx sequelize-cli` instead because it doesn't required to be packaged into a production build.

_Dependencies_

The `sequelize-cli` is having dependency on `sequelize` package.
```bash
npm install pg pg-hstore sequelize
```

## What have been done.

[X] Simply run `npm run sequelize:init`.
[ ] Configure .sequelizerc to store all db files into a `db` folder (to differentiate with the application codes).
    - This is because only partial files generated/referenced by `sequelize-cli` will be used in application codes as well.
    - We would like to create a reusable package for migration and application build.