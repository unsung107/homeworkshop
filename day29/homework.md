# homework 29

## 1번문제

1) 404 : 서버가 요청한 페이지(Resource)를 찾을 수 없다. 예를 들어 서버에 존재하지 않는 페이지에 대한 요청이 있을 경우 서버는 이 코드를 제공한다.

2) 405 : 요청에 지정된 방법을 사용할 수 없다. 예를 들어 POST 방식으로 요청을 받는 서버에 GET 요청을 보내는 경우, 또는 읽기 전용 리소스에 PUT 요청을 보내는 경우에 이 코드를 제공한다.

3) 500 : 서버에 오류가 발생하여 요청을 수행할 수 없다.



## 2번문제

```python
from django.shortcuts import get_object_or_404

def shorcuts(reqeust):
    ex = get_object_or_404(Example, pk=example_pk)

```



## 3번문제

1번

없다.