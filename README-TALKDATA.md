# Commands Note for TalkData project against picard

## Convert Mysql Database to Sqlite
```commandline
pip install mysql-to-sqlite3
mysql2sqlite --sqlite-file ./amazondb.sqlite --mysql-database amazondb --mysql-user bruce --mysql-password JGQsyx0106
mysql2sqlite --sqlite-file ./erpdb.sqlite --mysql-database erpdb --mysql-user bruce --mysql-password JGQsyx0106
mv amazondb.sqlite ./ecdbs/amazondb
mv erpdb.sqlite ./ecdbs/erpdb
```