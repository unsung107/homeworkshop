# workshop 25

```python
class Article(models.Model):
    
    title = models.CharField(max_length=20)
    content = models.TextField()

class Hashtag(models.Model):

    content = models.TextField()
    articles_hashtags = models.ManyToManyField(Article, related_name='hashtags')
```

