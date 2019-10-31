# workshop 31

```javascript

    const button = document.querySelector('#change-btn')
    const header = document.querySelector('h1')

    let clickCount = 0
    button.addEventListener('click', event => {
      
      header.innerText = ++clickCount
    }
    })
```

