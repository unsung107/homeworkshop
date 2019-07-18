## Homework

```python
def findroot(num, e = 5): #e는 원하는 정확도 자리수.
    if e>15:
        print('e가 너무 큽니다.')
        return 0

    root_floor = float(0)
    root_top = float(0)

    for i in range(1, num):
        if i ** 2 == num:
            return i

        if i ** 2 < num < (i + 1) ** 2:
            root_floor = i
            root_top = i + 1

    while num - root_floor ** 2 > 10 ** (-e): #차이가 원하는 숫자만큼 줄어든순간
        if root_floor ** 2 <= num < (float(root_floor + root_top) / 2) ** 2:
            root_top = float(root_floor + root_top) / 2
        else :
            root_floor = float(root_floor + root_top) / 2
        
    return (float(root_floor + root_top) / 2)

print(findroot(int(input()),int(input())))

----
입력 2, 7
출력 1.4142135977745056

입력 2, 15 (한계)
출력 1.4142135623730954
```

