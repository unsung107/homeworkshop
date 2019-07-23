## 1번문제

```
python 에서 기본적으로 정의되어있는 클래스

 1. list
 2. set
 3. int
 4. dict
 5. str
 ...
 
```

## 2번문제

```python
__init__ : 클래스의 객체가 생성되었을때 실행되는 것. 
#ex) 
__init__(self, name):
    self.name = name
    print(f'{self.name}이 클래스에 지정되었다')
 
__del__ : 인스턴스가 제거되었을때 실행되는것.
__del__(self, name):
    
    print(f'{self.name}이 죽었따')
    
__str__ : 객체를 print할때 보이는 값
__repr__ : 객체자체가 보여주는 값
    

```

## 3번문제

```
str.join(list) : str 문자열을 list 요소 사이에 넣어 문자열로 반환
str.split('?') : str 문자열내의 ? 마다 구분하여 리스트로 변환
str.strip() : str 문자열 좌 우에서 공백제거. (내부에 문자열 가능)

list.append(n) : 리스트에 n 추가
list.pop() : 리스트의 마지막 인덱스 삭제후 그 값 반환, (내부에 인덱스 가능)
list.sort() : 리스트요소 오름차순 정리(키값으로 reverse=True 시 내림차순)

dict.sort() : 사전의 키값으로 오름차순 정리(key= 설정으로 value기준으로 가능)
dict.get(키,디폴트) : 키의 값을 반환, 없으면 디폴트 반환
dict.keys() : 사전의 key값들을 반환
```



