### Install PostgreSQL in ubuntu
```
$ sudo apt-get install postgresql postgresql-contrib
```

### Check for PostgreSQL Services
```
$ service postgresql status
```

### Run PostgreSQL Services
```
$ service postgresql start
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
sudo su postgres
// postgres is a default user name
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
postgres=# CREATE USER USERNAMETOBEGIVEN WITH PASSWORD 'PASS'
// e.g USERNAMETOBEGIVEN = muiz
```

### Change password for a User
```
postgres=# ALTER USER postgres WITH PASSWORD 'PASS'
```

### Change user role for a User
```
postgres=# ALTER USER postgres WITH SUPERUSER
```

### Delete a User
```
postgres=# Drop USER USERNAME
```
