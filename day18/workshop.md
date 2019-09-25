## 1번 문제

``` sqlite
CREATE TABLE bands (
   ...>         id INTEGER PRIMARY KEY,
   ...>         name TEXT,
   ...>         debut INTEGER
   ...> );
   
INSERT INTO bands (name, debut)
   ...>         VALUES ("Queen", 1973), ("Coldplay", 1998), ("MCR", 2001);
```



## 2번 문제

```sqlite
SELECT id, name FROM bands;
```



## 3번 문제

```sqlite
SELECT NAME FROM bands WHERE debut < 2000;
```


