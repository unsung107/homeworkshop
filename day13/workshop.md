# workshop



urls.py

```python
urlpatterns = [
    path('info/', views.info),
    path('student/<str:name>/<int:age>/', views.student),
    path('admin/', admin.site.urls),
    ]
```

views.py

```python
def info(request):
    return render(request, 'info.html')

def student(request, name, age):
    context = {
        'name': name
        'age': age
    }
    return render(request, 'student.html', context)
```

info.html

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  <h1>우리반정보</h1>
   <h2>Teacher</h2>
     <ul>
       <li>Name</li>
     </ul>
  
  <h2>Student</h2>
  <ul>
    <li>홍길동</li>
    <li>김길동</li>
    <li>박길동</li>
  </ul>
</body>
</html>
```

student.html

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
</head>
<body>
  <h1>이름 : {{ name }}</h1>
  <h2>나이 : {{ age }}</h2>

</body>
</html>
```

