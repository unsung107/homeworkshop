## 1번문제

```python
n = 5
m = 9

for l in range(m):
    for i in range(n):
        print('*', end = '')
    print('')
    
*****
*****
*****
*****
*****
*****
*****
*****
*****

```

## 2번문제

```python
student = {
    'python' : 80,
    'algorithm' : 99,
    'django' : 89,
    'flask' : 83
}

print(sum(student.values())/len(student))


87.75
```

## 3번문제

```python
blood_type = ['A', 'B', 'A', 'O', 'AB', 'AB', 'O', 'A', 'B', 'O', 'B', 'AB']
result = {}

for i in blood_type:

    result[i] = 0

for i in blood_type:

    result[i] += 1

print(result)

{'A': 3, 'B': 3, 'O': 3, 'AB': 3}
```

