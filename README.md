
# mongodb-auto-backup

Basic mongo dump and restore commands, they contain more options you can have a look at man page for both of them.
1. mongodump --db=rbac_tutorial --archive=./rbac.gzip --gzip
2. mongorestore --db=rbac_tutorial --archive=./rbac.gzip --gzip

* Cron expression for every 5 seconds - */5 * * * * *
* Cron expression for every night at 00:00 hours (0 0 * * * )

```
Note: 2nd expression only contains 5 fields, since seconds is not necessary
```
