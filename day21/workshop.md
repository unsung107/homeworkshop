```python

choices = question.Choice_set.all()

context = {
    'choices': choices,
    'question': quesiton,
    
}
```

로 받아온 경우에

```html
{% for choice in choices %}
<p>{{ choice.content }}: {{choice.votes}}</p>
{% end for %}
```

