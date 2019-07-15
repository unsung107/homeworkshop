# Homework

## 1번문제

```python
import keyword
print(keyword.kwlist)

['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', ', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']

```

## 2번문제

```python
import math

a = 0.1 * 3
b = 0.3

print(math.isclose(a, b))

```

## 3번문제

```python
print('''
줄바꿈\\n \n
탭\t탭
\\''')
```

## 4번문제

```python
name = '철수'
print(f'안녕, {name}야')
print('안녕, %s야' %name)
print('안녕, {}야' .format(name))
```

## 5번문제

```python
# 5)
Traceback (most recent call last):
  File "Untitled-1.py", line 1, in <module>
    int('3.5')
ValueError: invalid literal for int() with base 10: '3.5'
        
# '3'과 같이 정수형 스트링만 integer로 형변환 가능
```

