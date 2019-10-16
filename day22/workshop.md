# workshop

```python
class Person(models.Model):
    name = models.CharField(max_length=10)
    email = models.CharField(
        max_length=100,
        validators=[EmailValidator(message='이메일 형식에 맞지 않습니다.')]
    )
    age = models.IntegerField(
        validators=[MinValueValidator(19, message='미성년자는 노노')]
    )
```

