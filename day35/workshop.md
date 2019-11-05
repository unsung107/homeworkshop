# workshop 35

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
      <!-- 도움되는 콘솔 경고를 포함한 개발 버전 -->
  <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
  <title>Document</title>
</head>
<body>
  <div id="app">
  <button v-on:click="increase">+1</button><br>
  <span>Counter : {{ count }}</span>
  </div>
  <script>
    const app = new Vue({
      el: '#app',
      data: {
        count: 0
      },
      methods: {
        increase: function() {
          this.count++
        }
      }
    })
    // const counterBtn = document.querySelector('#counter')
    // counterBtn.addEventListener('click', function(evnet) {
    //   const count = Number(counterBtn.innerText) + 1
    //   counterBtn.innerText = count
    // })
  </script>
</body>
</html>
```

