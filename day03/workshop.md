```python
word = input()

def palindrome(word):
    word = list(word)
    leng = len(word)
    
    check = 0

    for letter in range(leng):
        if word[letter] == word[leng-letter-1]:
            check += 1
    if check == leng:
        return True
    else : 
        return False

print(palindrome(word))

```

