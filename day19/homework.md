## 1번 문제

``` sqlite
sqlite> CREATE TABLE friends (
   ...> id INTEGER PRIMARY KEY AUTOINCREMENT,
   ...> name TEXT,
   ...> location TEXT
   ...> );
```



## 2번 문제

```sqlite
sqlite> INSERT INTO friends
   ...> VALUES (1, "Justin", "Seoul"), (2, "Simon", "New York"), (3, "Chang", "Las Vegas"), (4, "John", "Sydney");
```



## 3번 문제

```sqlite
sqlite> ALTER TABLE friends ADD COLUMN married;
```



## 4번 문제

```sqlite
sqlite> UPDATE friends
   ...> SET married=1
   ...> WHERE id=1;
sqlite> UPDATE friends
   ...> SET married=0
   ...> WHERE id=2;
sqlite> UPDATE friends
   ...> SET married=0
   ...> WHERE id=3;
sqlite> UPDATE friends
   ...> SET married=1
   ...> WHERE id=4;
```



