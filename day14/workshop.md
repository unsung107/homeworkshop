## workshop

urls.py

```python
urlpatterns = [
    path('num/push', views.push),
    path('num/pull/', views.pull),
    ]
```



views.py

```python
def push(request):
    return render(request, 'push.html')

def pull(request):
    num = request.GET.get('num')
    context = {
        'num': num,
    }
    return render(request, 'pull.html', context)
```



push.html

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Pull</title>
</head>
<body>
  <h1>Push number</h1>

  <form action="/num/pull/">
    <br/>
    <input type="text" name="num">
    <button type="submit">push!</button>
  </form>
</body>
</html>
```

result.html

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Push</title>
</head>
<body>
  <h1>Pull number</h1>
  <h2>Pull 해보니 {{ num }} 입니다.</h2>
  
</body>
</html>
```

