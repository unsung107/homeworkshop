```python
class Animal:
    def __init__(self, name):
        self.name = name
        
    def walk(self):
        print(f'{self.name}! 걷는다!')
    
    def eat(self):
        print(f'{self.name}! 먹는다!')
        
class Dog(Animal):
    
    def __init__(self, name):
        super().__init__(name)
        
    def run(self):
        print(f'{self.name}! 달린다!')
        
class Bird(Animal):
    
    def __init__(self, name):
        super().__init__(name)

    def fly(self):
        print(f'{self.name}! 푸드덕!')

dog = Dog('바둑이')
bird = Bird('구구')

dog.walk()
dog.run()
bird.walk()
bird.eat()
bird.fly()
```

