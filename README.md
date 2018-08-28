# Learning-MySQL
Learning MySQL



Creating Database <database-name>
```sh
$ mysql --user=root --password="" -e "CREATE DATABASE <database-name>"
```

Creating Database myblog
```sh
$ mysql --user=root --password="" -e "CREATE DATABASE myblog"
```

show databases
```sh
$ show databases;
```

use <database-name>
```sh
$ use <database-name>;
```
  
show tables
```sh
$ show tables;
```

show tables
```sh
$ create table noticias(
    -> id_noticia int not null primary key auto_increment,
    -> titulo varchar(100),
    -> noticia text,
    -> data_criacao timestamp default current_timestamp);

```

create table
```sh
$ create table noticias(id_noticia int not null primary key auto_increment, titulo varchar(100), noticia text, data_criacao timestamp default current_timestamp);
```

create table
```sh
$ create table noticias(id_noticia int not null primary key auto_increment, titulo varchar(100), noticia text, data_criacao timestamp default current_times
```

create table
```sh
$ insert into noticias(titulo, noticia)values('Titulo da Noticia', 'Conteudo da Noticia');
```

create table
```sh
$ select * from noticias;
```
