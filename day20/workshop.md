```python
class Question(models.Model):
    title = models.CharField(max_length=20)
    
class Choice(models.Model):
    question = models.ForeignKey(Question, on_delete=models.CASCADE)
    content = models.CharField(max_length=20)
    votes = models.IntegerField(blank=True, null=True)
    
```

