# PDOandActiveRecord
Тут разом и лаба PDO, и лаба Active Record.

- - - - - - - - - - - - - - - - - - - - - -

Таблица базы данных имеет следующий вид:

```
create table gachitable
(
id INT AUTO_INCREMENT, 
surname VARCHAR(20) NOT NULL,
name VARCHAR(20) NOT NULL,
fathername VARCHAR(20),
city VARCHAR(20),
rang VARCHAR(20),
ZarplataInBucks INT CHECK(ZarplataInBucks>=0),
PRIMARY KEY(id)
);
```

