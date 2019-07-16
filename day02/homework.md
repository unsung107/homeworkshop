## 1번문제

```python
imputable = ['String', (tuple), range()]
mutable = [[list], {set}, {dictionary}]
```

## 2번문제

```python
numbers = list(range(1,51))
goal = []

for i in numbers:
    if i % 2 == 1:
        goal.append(i)

print(goal)

[1, 3, 5, 7, 9, 11, 13, 15, 17, 19, 21, 23, 25, 27, 29, 31, 33, 35, 37, 39, 41, 43, 45, 47, 49]
```

## 3번문제

```python
classroom = {
    '김은성' : 27,
    '홍길동' : 26,
    '이학생' : 25,
}

print(classroom)

{'김은성': 27, '홍길동': 26, '이학생': 25}
```

