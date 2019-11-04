# workshop 34

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
    <ul>
      <li v-for="number in numbers" v-if="number % 2 == 0">{{ number }}</li>
    </ul>
  </div>

  <script>
    var app = new Vue({
      el: '#app',
      data: {
        numbers: [0,1,2,3,4,5,6,7,8,9],
      }
    })
  </script>
</body>
</html>
```



