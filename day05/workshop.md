## 1번문제

```python
calc.py

def plus(a, b):
    return a + b
def subject(a, b):
    return a - b
def times(a, b):
    return a * b
def divide(a, b):
    if b != 0:
        return a / b
    else:
        return '0으로는 나눌 수 없습니다.'

```

```python
import calc

calc.plus(2, 3)
calc.subject(2, 3)
calc.times(2, 3)
calc.divide(2, 3)

```

