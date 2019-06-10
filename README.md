# docs

### mysql 查看字段名和注释

```
select COLUMN_NAME,column_comment from INFORMATION_SCHEMA.Columns where table_name='table name' and table_schema='database name'

```

### 允许远程访问mysql `>= 8.0`
```

grant all privileges on db_name.* to root@'%' with grant option;

```



### Mysql8 

```bash
ALTER USER 'root’@‘localhost’ IDENTIFIED WITH mysql_native_password BY ‘password’;

```
