# Pellets Api

To start this API, create a .env file in the root of this folder with this content

```
NODE_ENV="development"
DATABASE_USERNAME="root"
DATABASE_PASSWORD=""
```

Update the username and password with the credentials of your local database.

You can also extend the .env file with these configurations, only if the database host/port are different than our default.

```
DATABASE_HOST="localhost"
DATABASE_PORT=3306
```
## How to start

Run the app with `yarn start`.

## Authenticatie

email: natanael.dobie@student.hogent.be
password: 12345678

## Common errors

* Modules not found errors, try this and run again:

```
yarn install
```
* Migrations failed, try dropping the existing `pellets` database and run again
* Testing : `pellets_test` database name

