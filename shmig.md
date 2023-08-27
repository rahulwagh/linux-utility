
## Login to postgressql
```
sudo -u postgres psql
sudo -u ubuntu psql
```

## Create empty sql file
```
./migrations/shmig -t postgresql -d ubuntu create mytable
```

## Run migrate command
```
./migrations/shmig -t postgresql -d ubuntu migrate
```

## List commands
```
\du - users
\dn - schema
\l  - list all database
\dt - list tables
```
