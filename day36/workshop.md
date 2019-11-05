# workshop 36

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <!-- 도움되는 콘솔 경고를 포함한 개발 버전 -->
  <script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
  <title>Vue start</title>
</head>
<body>
  
  <div id="app">
    <button v-on:click="toggle">Toggle</button>
    <div class="static" v-bind:style="{ color: color }">빨강과 파랑을 섞으면 보라색이 됩니다.</div>
    
  </div>


  <script>
    const app = new Vue({
      el: '#app', // 바인딩, 앞으로 여기의 데이터를 위의 app에 랜더링을 하겠다
      data: {
        color: 'red'
      },
      methods: {
        toggle() {
          if (this.color === 'red') {
            this.color = 'blue'
          } else {
            this.color ='red'
          }
        }
      }
    })
  </script>
</body>
</html>
```

