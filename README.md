# Learning-MySQL
Learning MySQL



Creating Database <database-name>
```sql
$ mysql --user=root --password="" -e "CREATE DATABASE <database-name>"
```

Creating Database myblog
```sh
$ mysql --user=root --password="" -e "CREATE DATABASE myblog"
```

show databases
```sql
$ show databases;
```

use <database-name>
```sql
$ use <database-name>;
```
  
show tables
```sql
$ show tables;
```

show tables
```sql
$ create table noticias(
    -> id_noticia int not null primary key auto_increment,
    -> titulo varchar(100),
    -> noticia text,
    -> data_criacao timestamp default current_timestamp);

```

create table
```sql
$ create table noticias(id_noticia int not null primary key auto_increment, titulo varchar(100), noticia text, data_criacao timestamp default current_timestamp);
```


insert
```sql
$ insert into noticias(titulo, noticia)values('Titulo da Noticia', 'Conteudo da Noticia');
```

select
```sql
$ select * from noticias;
```

alter
```sql
$ alter table noticias add column resumo varchar(100);
```
