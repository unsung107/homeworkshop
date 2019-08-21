# workshop

base.html

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
  <h1>Base is everywhere!</h1>
  {% block content %}
  {% endblock %}

</body>
</html>	
```



pages/one.html

```html
{% extends 'base.html' %}

{% block content %}
<h1>I am ONE!</h1>

{% endblock  %}

```



pages/two.html

```html
{% extends 'base.html' %}

{% block content %}
<h1>I am TWO!</h1>

{% endblock  %}

```

