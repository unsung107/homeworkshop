# Workshop day01

## 1번문제

```
n = 5
m = 9

line = '*'*n+'\n'

print(line*m)

```

## 2번문제

```python
print('"파일은  C:\\Windows\\Users\\내문서\\Python에 저장이 되어있습니다."\n나는 생각했다. \'cd를 써서 git bash로 들어가봐야지\'')
```

## 3번문제

```python
def solve(coefficient1,coefficient2,coefficient3):
	
    a = coefficient1
	b = coefficient2
	c = coefficient3
	
	D = (b**2-4*a*c)**0.5

	x, y = (-b-D)/(2*a), (-b+D)/(2*a)
	return x,y
    
print(solve(1,4,-21))

```

