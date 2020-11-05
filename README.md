# pg-test
Simple application to test whether freshly installed PostgreSQL database is accepting connections from NodeJS

One has to create a database and a table in it.

1. `npm install`
2. provide credentials, e.g. with `dotenv` – create **.env** file with the content like this:

```PGUSER=gdbadmin
PGHOST=127.0.0.1
PGPASSWORD=123456
PGDATABASE=mydatabase
PGPORT=5432
```

3. `node index.js`

