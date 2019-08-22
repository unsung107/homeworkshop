## 1번



models.py

```python
class Student(models.Model):
    
    name = models.CharField(max_length=20)
    email = models.CharField(max_length=20)
    birthday = models.DateField()
    age = models.IntergerField()
    
    def __str__(self):
        return f'{name}'
    

student1 = Student(name='학생1', email='1@naver.com', birthday=1994-6-16, age=14)
student1.save()
student2 = Student(name='학생2', email='2@naver.com', birthday=1993-6-16, age=15)
student2.save()
student3 = Student(name='학생3', email='3@naver.com', birthday=1992-6-16, age=16)
student3.save()
```

