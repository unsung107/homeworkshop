# workshop 27

bootstrap를 다운받는다

assets/에 압축을 푼다

```html
<!DOCTYPE html>
{% load static %}
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">

  <link rel="stylesheet" href="{% static 'bootsrap/css/bootstrap-reboot.min.css' %}">
  <link rel="stylesheet" href=" {% static 'bootsrap/css/bootstrap-grid.min.css' %}">

```

```html
  <script src="{% static 'bootstrap/js/bootstrap.bundle.min' %}"></script>
```

