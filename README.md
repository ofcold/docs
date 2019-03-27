# docs

### mysql 查看字段名和注释

```
select COLUMN_NAME,column_comment from INFORMATION_SCHEMA.Columns where table_name='table name' and table_schema='database name'

```
