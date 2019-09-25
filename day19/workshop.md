## 1번 문제

``` sqlite
sqlite> ALTER TABLE bands ADD COLUMN members INTEGER;
sqlite> UPDATE bands
   ...> SET members=4
   ...> WHERE id=1;
sqlite> UPDATE bands
   ...> SET members=5
   ...> WHERE id=2;
sqlite> UPDATE bands
   ...> SET members=9
   ...> WHERE id=3;
```



## 2번 문제

```sqlite
sqlite> UPDATE bands
   ...> SET members=5
   ...> WHERE id=3;
```



## 3번 문제

```sqlite
sqlite> DELETE FROM bands WHERE id=2;
```


