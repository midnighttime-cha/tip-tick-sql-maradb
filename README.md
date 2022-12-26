#   รวม SQL และวิธีแก้ปัญหาของ MariaDB

## DUMP Database
```sql
mysqldump -u root -p --compress --debug-info=false --result-file=/home/[My USER]/[FILE_DUMP].dump --lock-tables=false --routines --databases [DB_NAME]
```
