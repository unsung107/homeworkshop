## 1번문제

```
인스턴스 메서드:
def info(self) => 데코레이터가 없을시 인스턴스 메서드 취급

스태틱 메서드
def add(a, b) => self 혹은 cls 인자가 없고, @staticmethod 데코레이터

클래스 메서드
def history(cls) => self 대신 cls 인자받고, @classmethod 데코레이터

```

## 2번문제

```python
cal = Calculator()

cal.info()

Calculator.add(1, 2)

Calculator.history()
```

## 3번문제

```
self : 클래스의 인스턴스가 된 객체 그 자신
cls : Calculator 클래스 객체 자신이 할당된다
```

