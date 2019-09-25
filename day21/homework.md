## 1번문제



```python
#views.py/detail()
comments = Question.Comment_set.all()

context = {
    'comments': comments
}
```



```html
 {% for comment in comments %}
  <h3>{{ comment.content }}</h3>
  {% empty %}
  <p>아직 댓글이 없습니다.</p>
 {% endfor %}
```



## 2번문제

app_name = 'articles' / article을 article 이란 이름으로 받아왔을경우

```html
<form action="{% url 'articles:comments_create' article.pk %}" method="post">
{% csrf_token %}
    
```

