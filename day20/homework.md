

## 1 번문제



```python
class School(models.Model):
    
class Student(models.Model):
    school = models.ForeignKey(School, on_delete=models.CASCADE)

```



## 2번문제

```python
comments = question.Comment_set.all()
```



## 3번문제

