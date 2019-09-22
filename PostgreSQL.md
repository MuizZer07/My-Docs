### Install PostgreSQL in ubuntu
```
$ sudo apt-get install postgresql postgresql-contrib
```

### Check for PostgreSQL Services
```
$ service postgresql status
```

### Run PostgreSQL Services (ubuntu)
```
$ service postgresql start
```

### Run PostgreSQL Services (ubuntu)
```
$ pg_ctl -D /usr/local/var/postgres start
```

### Stop PostgreSQL Services
```
$ service postgresql stop
```

### PostgreSQL docs
```
$ man psql
```

### Enter/login a user profile to access Databases
```
$ sudo su postgres
// postgres is a default user name
```

### Create new database (mac)
```
$ createdb DB_NAME
```

### Enter command line tool / shell
```
$ psql
```

## In Postgres Shell

### List of databases
```
postgres=# \l
```

### List of users
```
postgres=# \du
```

### Create a new User
```
postgres=# CREATE ROLE USERNAMETOBEGIVEN WITH PASSWORD 'PASS'
// e.g USERNAMETOBEGIVEN = muiz
```

### Create user with role
```
$ CREATE ROLE bms_1 WITH CREATEDB SUPERUSER LOGIN ENCRYPTED PASSWORD '1q2w3e';
```

### Change password for a User
```
postgres=# ALTER USER postgres WITH PASSWORD 'PASS'
```

### Change user role for a User
```
postgres=# ALTER USER postgres WITH SUPERUSER
```

```
$ ALTER USER user_name WITH PASSWORD 'new_pass' GRANT ALL PRIVILEGES ON DATABASE bms TO bms;
```

### Delete a User
```
postgres=# Drop USER USERNAME
```
